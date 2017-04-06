# Third-Party Files
ZeroBundle is a convenient package that makes ZeroNet portable. Since all required libraries are packed into the bundle, packaging gets so complicated that it is super easy to fail to keep all dependencies up-to-date.

This repository keeps track of ZeroNet's use of third-party libraries. It lists as thoroughly as possible the third-party source code and binaries required to run [ZeroBundle](https://github.com/HelloZeroNet/ZeroBundle) and [ZeroNet](https://github.com/HelloZeroNet/ZeroNet).

## Repository Status
The current listing is not yet complete.

## Included in ZeroNet
As of **April 6, 2017**, these libraries are included in `ZeroNet/src/lib/`.

| Status | Included library | Library last release | Library last updated in ZeroNet |
| ------ | ---------------- | -------------------- | ------------------------------- |
| **Inactive** | [BitcoinECC](https://github.com/HurlSly/BitcoinECCPython) | 2 years ago | 2 years ago |
| **Too Old** | [PySocks](https://github.com/Anorov/PySocks) | 14 days ago (Mar 23, 2017) | 2 years ago |
| ? | bencode | ? | 2 years ago |
| ? | cssvendor | ? | 1 year ago |
| **Too Old** | [gevent-websocket](https://github.com/jgelens/gevent-websocket/releases) | 24 days ago (Mar 12, 2017) | 2 years ago |
| **Too Old** | [OpenSSL](https://www.openssl.org/source/) Win32 | Jan 26, 2017 (1.0.2k) | Oct 01, 2016 (1.0.2j) |
| **Old** | [opensslVerify](https://github.com/Bitmessage/PyBitmessage/blob/master/src/pyelliptic/openssl.py) | Feb 18, 2017 | Jan 22, 2017 |
| **Too Old** | [pyasn1](https://github.com/etingof/pyasn1) | Feb 25, 2017 (0.2.3) | Jan 4, 2016 (0.1.7) |
| **Old** | [pybitcointools](https://github.com/vbuterin/pybitcointools) | Nov 22, 2016 (alpha) | Jun 9, 2015 |
| **Inactive** | [pyelliptic](https://github.com/yann2192/pyelliptic) | Aug 31, 2015 | Dec 10, 2015 |
| **Too Old** | [Python-RSA](https://github.com/sybrenstuvel/python-rsa) | Mar 29, 2016 (3.4.2) | Jan 4, 2016 (3.1.1) |
| Inactive | [subtl](https://github.com/packetloop/subtl) | Oct 10, 2012 | Jan 19, 2016 |

These libraries are included in `ZeroNet/tools/`.

| Status | Included library | Library last release | Library last updated in ZeroNet |
| ------ | ---------------- | -------------------- | ------------------------------- |
| Too Old | [CoffeeScript compiler](https://github.com/jashkenas/coffeescript) | Feb 18, 2017 (1.12.4) | Oct 19, 2015 (1.10.0) |
| Note | [Tor](https://torproject.org) | Will download from TorProject.org | The user has to [manually update](https://github.com/HelloZeroNet/ZeroNet/blob/master/tools/tor/manual_install.txt) Tor |

## Included in ZeroBundle Windows
As of **April 6, 2017**, these libraries are included in `ZeroBundle/dist/ZeroBundle-win.zip`.

| Status | Included library | Library last release | Library last updated in ZeroNet |
| ------ | ---------------- | -------------------- | ------------------------------- |
| OK | [Python](https://python.org) | 2.7.12 | 2.7.12 |
| todo | [gevent](https://pypi.python.org/pypi/gevent#downloads) | Jan 12, 2017 | ? |
| todo | [msgpack-python](https://github.com/msgpack/msgpack-python) | Mar 12, 2015 (0.4.6) | ? |
| todo | More...? | | |

