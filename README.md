# ethervineAlpha

[In response to the idle workers problem](https://mohamedhayibor.github.io/blog/post/Update-on-Idle-Workers-Problem-6-13-18/)

> [Master branch testing with Rinkeby](https://mohamedhayibor.github.io/ethervineAlpha/)


FAQ
----

* Users can only create or trade memes
* No shorting / only buying or selling of tokens
* Each meme is a PolynomialBondingCurve
* Memes are non tradable between users - only to the smart contract

Testing Rinkeby Accts
------

1. [Meme Recorder](https://rinkeby.etherscan.io/address/0xb93eddce16ae43790eafd7ebee8a5bcf40f46bb5)
2. [meme exple](https://rinkeby.etherscan.io/address/0xdb47329fb71dc1dfe3245610d6f8d1b59cc28eef)


Dev setup:
========

For local development, you must run a local server for security reasons and constraints on [metamask](https://github.com/MetaMask/faq/blob/master/DEVELOPERS.md#globe_with_meridians-https---web-server-required), IPFS...

Easy/fast way: go to source path

```sh
$ python -m SimpleHTTPServer
```

Then go to [localhost:8000](http://localhost:8000/)