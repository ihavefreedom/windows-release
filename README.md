# ihavefreedom for Windows

Installer and updates for the ihavefreedom client.

**[Download the latest release](https://github.com/ihavefreedom/windows-release/releases/latest)**

| file | what it is |
| --- | --- |
| `ihf-setup.exe` | the installer — this is the one you want |
| `ihf.zip` | the same binaries without an installer |
| `latest.json` | update manifest the client reads on start |

Once installed, the client checks this repository on start and updates itself.

## License

The client is proprietary — see [LICENSE](LICENSE).

It ships with two third-party cores. Each is an unmodified upstream build with
only the file name changed, and each stays under its own license:

| file | project | version | license |
| --- | --- | --- | --- |
| `ihf-singbox.exe` | [sing-box](https://github.com/SagerNet/sing-box) | 1.14.0 | GPL-3.0-or-later |
| `ihf-xray.exe` | [Xray-core](https://github.com/XTLS/Xray-core) | 26.7.28 | MPL-2.0 |

Their license texts are installed next to the client, in `licenses\`. Source
code for both is published by their authors at the projects linked above.
