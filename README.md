# Ethereum-2 Notification Bot
This script monitors the status of the Ethereum-2 node and notifies the Telegram Bot if the node stops syncing or goes down.

### Prerequisites

* curl
* jq
```
sudo apt-get install curl jq
```
### Installing

```sh
git clone https://github.com/everstake/ethereum2-notificationbot.git
cd ethereum2-notificationbot
chmod +x notifier.sh
```
### Configuration

Edit configuration file `config.ini`.

### Node Configuration

Start node with --monitoring-host 0.0.0.0 key.

## Running
Run a command
```sh
./notifier.sh
```
