KatKoyn Core 2.0
=====================

Setup
---------------------
[KatKoyn Core](http://katkoyn.com/) is the reference KatKoyn client and it builds the backbone of the network. However, it downloads and stores the entire history of Bitcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run KatKoyn on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/katkoyn-qt` (GUI) or
- `bin/katkoynd` (headless)

### Windows

Unpack the files into a directory, and then run katkoyn-qt.exe.

### OS X

Drag KatKoyn-Core to your applications folder, and then run KatKoyn-Core.

### Need Help?

* Ask for help on the [KatKoyn Telegram channel](https://t.me/katkoyns).
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [KatKoyn thread](https://bitcointalk.org/index.php?topic=1636509.0).
* Ask for help on the [KatKoyn subreddit](https://www.reddit.com/r/katkoyns/).

Building
---------------------
The following are developer notes on how to build KatKoyn on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)

Development
---------------------
The KatKoyn repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [KatKoyn thread](https://bitcointalk.org/index.php?topic=1636509.0).
* Discuss on [KatKoyn Telegram channel](https://t.me/katkoyns).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the Bitcoin developers for use in [KatKoyn Core](https://www.bitcoin.org/). 
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
