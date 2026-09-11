# ihavefreedom for Windows

Installer and updates for the ihavefreedom client.

**[Download the latest release](https://github.com/ihavefreedom/windows-release/releases/latest)**

| file | what it is |
| --- | --- |
| `ihf-setup.exe` | the installer — this is the one you want |
| `ihf.zip` | the same binaries without an installer |
| `latest.json` | update manifest the client reads on start |
| `Xray-core-*-source.zip`, `sing-box-*-source.zip` | complete source code of the bundled cores |

Once installed, the client checks this repository on start and updates itself.

## License

The client is proprietary — see [LICENSE](LICENSE).

It ships with two third-party cores. Each is an unmodified upstream build with
only the file name changed, and each stays under its own license:

| file | project | version | license |
| --- | --- | --- | --- |
| `ihf-singbox.exe` | [sing-box](https://github.com/SagerNet/sing-box) | 1.14.0 | GPL-3.0-or-later |
| `ihf-xray.exe` | [Xray-core](https://github.com/XTLS/Xray-core) | 26.7.28 | MPL-2.0, with GPL-3.0-or-later parts inside |

The Xray-core build also contains `github.com/sagernet/sing` and
`sing-shadowsocks`, which are GPL-3.0-or-later, so that binary as a whole is
covered by the GPL as well.

The complete source code of exactly these builds is attached to every release,
next to the installer, and is also published by their authors at the projects
linked above.

The client itself is built on open-source components compiled into `ihf.exe`:
Go packages, the interface libraries (React, React Aria and others) and the
Nunito Sans font. They are listed with their licenses in
`THIRD-PARTY-NOTICES.txt`.

All license texts are installed next to the client, in `licenses\`, and are
included in `ihf.zip`.
