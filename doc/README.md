ViptoCoin
=====================

Setup
---------------------
[ViptoCoin](https://viptocoin.com/) is the original viptocoin client and it builds the backbone of the network. However, it downloads and stores the entire history of viptocoin transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from one to two hours. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run ViptoCoin on your native platform.

### Unix

Unpack the files into a directory and run in terminal:

- ./viptocoin-qt (GUI, 32-bit) or ./viptocoind (headless, 32-bit)
- ./viptocoin-qt (GUI, 64-bit) or ./viptocoind (headless, 64-bit)

### Windows

Run the installer, and then run viptocoin-qt.exe.

### OSX

Drag viptocoin-Qt to your applications folder, and then run viptocoin-Qt.


### Miscellaneous

- [Files](files.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
