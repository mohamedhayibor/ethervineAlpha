# ethervineAlpha

[In response to the idle workers problem](https://mohamedhayibor.github.io/blog/post/Update-on-Idle-Workers-Problem-6-13-18/)

Technical scope:
---

* Each meme is a PolynomialBondingCurve
* Memes are non tradable by users
* Viewers (admirers) buy tokens from contract (bonding curve mechanism) to vote

> For each meme traded on mint and burn, creator can buy more of their meme if they feel like their meme will perform great.


Limitations
---

Users can only do 3 things.

```
 MemeRecorder -> Add Meme

 Meme         -> Mint or Burn
```


Only 4 user Buttons
---

* Choose image
* Create Meme
* Mint
* Burn


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