Nebulacoin Core
=============

Setup
---------------------
Nebulacoin Core is the original Nebulacoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Nebulacoin transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Nebulacoin Core, visit [nebulacoin.org](https://nebulacoin.org).

Running
---------------------
The following are some helpful notes on how to run Nebulacoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/nebulacoin-qt` (GUI) or
- `bin/nebulacoind` (headless)

### Windows

Unpack the files into a directory, and then run nebulacoin-qt.exe.

### OS X

Drag Nebulacoin-Core to your applications folder, and then run Nebulacoin-Core.

### Need Help?

* See the documentation at the [Nebulacoin Wiki](https://nebulacoin.info/)
for help and more information.
* Ask for help on [#nebulacoin](http://webchat.freenode.net?channels=nebulacoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=nebulacoin).
* Ask for help on the [NebulacoinTalk](https://nebulacointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Nebulacoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Nebulacoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/nebulacoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [NebulacoinTalk](https://nebulacointalk.io/) forums.
* Discuss general Nebulacoin development on #nebulacoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=nebulacoin-dev).

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
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
