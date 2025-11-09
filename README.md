# wkhtmltox 0.12.6.1 (Patched Qt) for Ubuntu 22.04 (Jammy)

A preserved and repacked version of [wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf),  
recompiled from an existing Ubuntu 22.04 installation using `dpkg-repack`.

This package provides a stable, **patched-Qt** build of `wkhtmltopdf` for modern Ubuntu systems —  
a version no longer available from the official releases.

---

## ⚙️ Build Details
- **Base package:** wkhtmltox 0.12.6.1 (with patched Qt)
- **Platform:** Ubuntu 22.04 LTS (Jammy)
- **Architecture:** amd64
- **Original source:** [wkhtmltopdf/packaging](https://github.com/wkhtmltopdf/packaging)
- **Repacked using:** `dpkg-repack`
- **License:** [LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html)

---

## 📦 Installation (Ubuntu 22.04)
```bash
wget https://github.com/karthikkm007/wkhtmltox-0.12.6.1-patched-qt-ubuntu-jammy/raw/main/wkhtmltox_0.12.6.1-2.jammy_amd64.deb
sudo dpkg -i wkhtmltox_0.12.6.1-2.jammy_amd64.deb
sudo apt -f install
wkhtmltopdf -V
# wkhtmltopdf 0.12.6.1 (with patched qt)
```
📚 Notes
This file was repacked solely to preserve access to a stable, patched version of wkhtmltopdf for Ubuntu Jammy users.
Full credit to the original wkhtmltopdf maintainers and contributors. (https://github.com/wkhtmltopdf/wkhtmltopdf)
This repository exists only for archival and convenience purposes.
