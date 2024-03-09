VirsAI Core
==========

This is the official reference wallet for VirsAI digital currency and comprises the backbone of the VirsAI peer-to-peer network. You can [download VirsAI Core](https://www.virsai.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run VirsAI Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/virsai-qt` (GUI) or
- `bin/virsaid` (headless)

### Windows

Unpack the files into a directory, and then run virsai-qt.exe.

### macOS

Drag VirsAI Core to your applications folder, and then run VirsAI Core.

### Need Help?

* See the [VirsAI documentation](https://docs.virsai.org)
for help and more information.
* Ask for help on [VirsAI Discord](http://stayvirsaiy.com)
* Ask for help on the [VirsAI Forum](https://virsai.online//forum)

Building
---------------------
The following are developer notes on how to build VirsAI Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The VirsAI Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* See the [VirsAI Developer Documentation](https://virsai.readme.io/)
  for technical specifications and implementation details.
* Discuss on the [VirsAI Forum](https://virsai.online//forum), in the Development & Technical Discussion board.
* Discuss on [VirsAI Discord](http://stayvirsaiy.com)
* Discuss on [VirsAI Developers Discord](http://chat.virsaidevs.org/)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [virsai.conf Configuration File](virsai-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [I2P Support](i2p.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [PSBT support](psbt.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
