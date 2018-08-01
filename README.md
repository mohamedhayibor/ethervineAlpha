# ethervineAlpha

[In response to the idle workers problem](https://mohamedhayibor.github.io/blog/post/Update-on-Idle-Workers-Problem-6-13-18/)

> [Master branch testing with Rinkeby](https://mohamedhayibor.github.io/ethervineAlpha/)


FAQ
----

* Users can only create or trade memes
* No shorting / only buying or selling of tokens
* Each meme is a PolynomialBondingCurve
* Memes are non tradable between users - only to the smart contract
* Each meme is its own communal deposit
* Curate memes with your own proportional backing

Interesting reads:
-----

* [Introduction to curation markets by Simondlr](https://medium.com/@simondlr/introducing-curation-markets-trade-popularity-of-memes-information-with-code-70bf6fed9881)
* [Not Cash but Work In](https://media.consensys.net/developing-micro-economies-via-work-in-not-buy-in-9f15b28f4126)

Testing Rinkeby Accts
------

1. [Meme Recorder](https://rinkeby.etherscan.io/address/0xb93eddce16ae43790eafd7ebee8a5bcf40f46bb5)
2. [meme exple](https://rinkeby.etherscan.io/address/0xdb47329fb71dc1dfe3245610d6f8d1b59cc28eef)


The hypothesis we're testing is that meme makers will use our site instead of others because they can earn money with this.


Dev setup:
========

For local development, you must run a local server for security reasons and constraints on [metamask](https://github.com/MetaMask/faq/blob/master/DEVELOPERS.md#globe_with_meridians-https---web-server-required), IPFS...

Easy/fast way: go to source path

```sh
$ python -m SimpleHTTPServer
```

Then go to [localhost:8000](http://localhost:8000/)