<h1 align="center">
<img src="https://i.imgur.com/XpJV4kF.png" alt="Tweetcoin" width="1000"/>
<br/><br/>
Tweetcoin Core [TWTC]
</h1>

<div align="center">


</div>

Tweetcoin is a community-driven cryptocurrency that was inspired by a Bitcoin and Litecoin. The Tweetcoin Core software allows anyone to operate a node in the Tweetcoin blockchain networks and uses the Scrypt hashing method for Proof of Work. It is adapted from Bitcoin Core and other cryptocurrencies.

For information about the default fees used on the Tweetcoin network, please
refer to the [fee recommendation](doc/fee-recommendation.md).

**Website:** [tweetcoin.us](https://tweetcoin.us/)

## Usage 💻

To start your journey with Tweetcoin Core, see the [installation guide](INSTALL.md) tutorial.

The JSON-RPC API provided by Tweetcoin Core is self-documenting and can be browsed with `tweetcoin-cli help`, while detailed information for each command can be viewed with `tweetcoin-cli help <command>`. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Such ports

Tweetcoin Core by default uses port `2222` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `2223` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |  2222   |  4444   |  5555   |
| RPC      |  2223   |  4445   |  5556   |

## Ongoing development

Tweetcoin Core is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software.

Main development resources:

* [GitHub Projects](https://github.com/Tweetcoin/tweetcoin/projects) is used to
  follow planned and in-progress work for upcoming releases.

## Communities 🚀🍾

You can join the communities on different social media.
To see what's going on, meet people & discuss, learn
about Tweetcoin, give or ask for help, to share your project.

Here are some places to visit:

* [Discord](https://discord.gg/buMU4cM25C)
* [Telegram](https://t.me/tweetcoinofficial)
* [Tweetcoin Twitter](https://twitter.com/TWTCofficial)



## License ⚖️
Tweetcoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)

