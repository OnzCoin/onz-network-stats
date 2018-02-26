# Onz Network Stats

This is a visual interface for tracking onz network status. It uses WebSockets to receive stats from running nodes and output them through an angular interface. It is the front-end implementation for [onz-network-reporter](https://github.com/OnzCoin/onz-network-reporter).

![Screenshot](https://raw.githubusercontent.com/OnzCoin/onz-network-stats/master/onz-network-stats-screenshot.png)

## Installation

<pre>
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash
export NVM_DIR="/root/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"  # This loads nvm
nvm install 6.2.0
git clone https://github.com/OnzCoin/onz-network-stats
cd onz-network-stats
npm install
</pre>

## Build

<pre>
npm run build
</pre>

## Configure

Change [secret key](https://github.com/OnzCoin/onz-network-stats/blob/ebe44d877eada5494fb0ad0cf594a33080a46599/app.js#L7)

## Run

<pre>
PORT=3010 npm start
</pre>

see the interface at http://localhost:3010

## Credits

Thanks to [cuberdo](https://github.com/cubedro/) and his [eth-netstats](https://github.com/cubedro/eth-netstats). This software has been created on the top of his work.
