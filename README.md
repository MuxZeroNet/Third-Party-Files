# Third-Party Files
ZeroBundle is a convenient package that makes ZeroNet portable. Since all required libraries are packed into the bundle, packaging gets so complicated that it is super easy to fail to keep all dependencies up-to-date.

This repository keeps track of ZeroNet's use of third-party libraries. It lists as thoroughly as possible the third-party source code and binaries required to run [ZeroBundle](https://github.com/HelloZeroNet/ZeroBundle) and [ZeroNet](https://github.com/HelloZeroNet/ZeroNet).

## Repository Status
The current listing is not yet complete.

## News
**Apr 7, 2017.** A majority of outdated libraries are being replaced with up-to-date libraries. In addition, the ZeroNet developer plans to remove the unmaintained BitcoinEEC library from the source code. Users and packagers should update ZeroNet.

**Apr 8, 2017.** ZeroNet on Windows now uses OpenDEC compiled OpenSSL binaries. The old PySocks library is used in ZeroNet source code due to a monkey patching issue. [Help us investigate it.](https://github.com/HelloZeroNet/ZeroNet/issues/893)

**Apr 25, 2017.** PyElliptic has been **abandoned**. Developers, please consider using another wrapper or crypto library, such as [pyOpenSSL](https://pypi.python.org/pypi/pyOpenSSL), [cryptography](https://cryptography.io/en/latest/), [PyNaCl](https://pynacl.readthedocs.io/) or [pySodium](https://github.com/stef/pysodium). Here is a crypto library choice discussion among Ethereum devlopers: [ethereum/pydevp2p#58](https://github.com/ethereum/pydevp2p/issues/58)

## Included in ZeroNet
As of **June 24, 2017**, these libraries are included in `ZeroNet/src/lib/`.

| Status | Included library | Library last release | Library last updated in ZeroNet |
| ------ | ---------------- | -------------------- | ------------------------------- |
| **Inactive** | [BitcoinECC](https://github.com/HurlSly/BitcoinECCPython) | 2 years ago | 2 years ago |
| **Old** | [PySocks](https://github.com/Anorov/PySocks) | Mar 23, 2017 (1.6.7) | Apr 8, 2017 **(1.5.3)** |
| ? | bencode | ? | 2 years ago |
| ? | cssvendor | ? | 1 year ago |
| OK | [gevent-websocket](https://github.com/jgelens/gevent-websocket/releases) | Mar 12, 2017 (0.10.1) | Apr 6, 2017 (0.10.1) |
| **Outdated** | [OpenSSL](https://www.openssl.org/source/) Win32 | May 25, 2017 (1.0.2l) | Apr 6, 2017 (1.0.2k) |
| **Old** | [opensslVerify](https://github.com/Bitmessage/PyBitmessage/blob/master/src/pyelliptic/openssl.py) | Feb 18, 2017 | Jan 22, 2017 |
| OK | [pyasn1](https://github.com/etingof/pyasn1) | Apr 6, 2017 (0.2.4) | Apr 6, 2017 (0.2.4) |
| OK | [pybitcointools](https://github.com/vbuterin/pybitcointools) | Nov 22, 2016 (1.1.42) | Apr 6, 2017 (1.1.42) |
| **DEPRECATED** | [pyelliptic](https://github.com/yann2192/pyelliptic/issues/50#issuecomment-297018932) | Aug 31, 2015 (1.5.7) | Apr 6, 2017 |
| OK | [Python-RSA](https://github.com/sybrenstuvel/python-rsa) | Mar 29, 2016 (3.4.2) | Apr 6, 2017 (3.4.2) |
| Inactive | [subtl](https://github.com/packetloop/subtl) | Oct 10, 2012 | Jan 19, 2016 |

These libraries are included in `ZeroNet/tools/`.

| Status | Included library | Library last release | Library last updated in ZeroNet |
| ------ | ---------------- | -------------------- | ------------------------------- |
| OK | [CoffeeScript compiler](https://github.com/jashkenas/coffeescript) | May 15, 2017 (1.12.6) | Jun 13, 2017 (1.12.6) |
| Note | [Tor](https://torproject.org) | Will download from TorProject.org | The user has to [manually update](https://github.com/HelloZeroNet/ZeroNet/blob/master/tools/tor/manual_install.txt) Tor |

## Included in ZeroBundle Windows
As of **June 24, 2017**, these libraries are included in `ZeroBundle/dist/ZeroBundle-win.zip`.

| Status | Included library | Library last release | Library last updated in ZeroNet |
| ------ | ---------------- | -------------------- | ------------------------------- |
| OK | [Python](https://python.org) | 2.7.13 | 2.7.12 |
| todo | [gevent](https://pypi.python.org/pypi/gevent#downloads) | Jun 5, 2017 (1.2.2) | ? |
| todo | [msgpack-python](https://github.com/msgpack/msgpack-python) | Mar 12, 2015 (0.4.6) | ? |
| todo | More...? | | |

