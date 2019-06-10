# Node-Monitor
The Node.js-based network and local node health monitor for ZENZO (ZNZ)

## Installation

1. `git clone https://github.com/ZENZO-Ecosystem/Node-Monitor`
2. cd `Node-Monitor`
3. `npm i express bitcoin-rpc-promise`
4. `nano index.js` (Edit local variables to suit your node RPC installation)


## Usage

After installing, start the health monitoring server using:

`node index`

And visit:

`localhost:3000/health`

In your internal browser, to view your node health statuses.

To view the health or pull it's stats remotely, simply replace `localhost` with the public IP of the server, and make sure your firewalls and iptable allows for external HTTP connections to port 3000 (Default port).
