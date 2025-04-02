# FAQ (WIP)

### What are the benefits of running minipools with Rocket Pool compared to a 32 ETH solo validator?

By running a single solo validator, you would receive 100% rewards on your 32 ETH.
By running two 16 ETH minipools, you would receive 100% rewards on your 32 ETH **plus** 14% of the rewards on 32 ETH provided by the Rocket Pool protocol.
By running four 8 ETH minipools, you would receive 100% rewards on your 32 ETH **plus** 14% of the rewards on 96 ETH provided by the Rocket Pool protocol.
You would also have the option to use Rocket Pool's [Smoothing Pool](./prepare-node.mdx#smoothing-pool) feature.

### How do I know how much my rETH is worth? Does it rebase?

The rETH token will not rebase.
The number of tokens on your wallet will remain constant but they appreciate in value over time.
You can check [here](https://rocketscan.io/reth) for more information on the exchange rate history.

### I have a technical issue running my node, how do I get help?

You can start by checking the [Rocket Pool Support](https://rocketpool.support) page.
If that doesn't help, you can ask your question on the Rocket Pool **#support** channel in [the Discord server](https://discord.gg/rocketpool).

### How can I get test ETH to experiment with creating and running a minipool? I can't post messages on the faucet channel.

See [Getting test ETH on Hoodi](../testnet/overview#getting-test-eth-on-hoodi).

### How do I recover my node if my machine breaks?

Short answer: your mnemonic is all that you need to fully recover your node.
Always make sure to keep it safe.

To recover your node on a new machine, start by making sure **your previous machine is not going to be online again** with the keys available, as two nodes running with the same keys **will get you slashed**.
Follow the [steps](./install-modes) to install the Smartnode on a new machine.
Then, recover your node wallet and validator keys by running the command `rocketpool wallet recover` and insert your 24-word mnemonic.

### Why aren't my clients syncing? I have a low amount of peers.

Clients need to have a healthy number of peers to be able to properly sync.
You can start by running the test [here](https://www.yougetsignal.com/tools/open-ports/), checking if ports 30303 and 9001 are opened.
If they're closed, you'll need to setup port forwarding on your router.
Also, make sure your node has a static local IP address so the port forwarding does not break due to your node getting a new address.

### My consensus client is taking too long to sync. What should I do?

Consensus clients can take a long time to sync if you didn't start the sync process using [Checkpoint Sync](./config-docker#beacon-chain-checkpoint-syncing).
Even if you're running it for a long time, it's usually faster to configure the checkpoint sync URL, clear the current sync data with `rocketpool service resync-eth2` and start over.
Your client should be synced in less than a minute.

### I've already rebooted. Why does Grafana say I still need to reboot?

The reboot information is cached and only updates every few hours.
Running `sudo apt update` will force an update.

### I changed my Execution Layer and/or my Beacon Chain or Consensus Layer. How do I clean out the old data?

If you change clients, Rocketpool does not delete the old volumes. This data could be wasting significant disk space and you may want to remove it. To do so, you need to find the volumes. If you are using the default Rocketpool settings, the docker volumes are stored at `/var/lib/docker/volumes/`. The execution layer is in `rocketpool_eth1clientdata/_data/*` and the consensus layer is in `rocketpool_eth2clientdata/_data/*`.

To access these directories, you may need to sudo as root using `sudo -i`. Then you can delete a directory by calling `rm -rf <directory>`. For example, if you wanted to delete all the geth data, you would call `rm -rf /var/lib/docker/volumes/rocketpool_eth1clientdata/_data/geth/`.

To exit as root, type `exit`.
