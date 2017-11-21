---
title: "Prüfsummen"
---

<div class="pageNavigation">
<div style="float:left;">
   [◀️ Home](index.md)
</div>
<div style="float:right;">
  [Installation ▶️](installation.md)
</div>
</div>

---------------
__Inhalt__
* TOC
{:toc}
---------------

To make certain that no one has modified the software between the time of creation and the time you wish to install it, you can calculate the MD5 (Message-Digest algorithm 5) checksum and compare your result to the MD5 checksum published in the table below. If the file has not been modified by some sinister malware person, the checksums will match. Otherwise you should delete this file and download it directly form the official download page.

To learn more about Checksum, visit [Wikipedia.org](https://en.wikipedia.org/wiki/Checksum).

## Version 1.4.0

| File name | MD5 Checksum |
|:--------|:-------:|
| ST-32bit-setup-v1-4-0.exe | b59a6d591b9cd65b806239bc2512163e |
| ST-32bit-v1-4-0.dmg | 74111fd51306b48e2dc7d8d543337ab4 |
| ST-64bit-setup-v1-4-0.exe | e89dab1a21ef797ed805217f4feb9708 |
| ST-64bit-v1-4-0.dmg | 1d75b512a70177d234b76ad3b53ef7ce |
| ST-Tiger-32bit-v1-4-0.dmg | 7865a9a98971407a49b7c866669a9944 |

## Create a checksum on macOS
Open the terminal, switch to the directory that contains the file to check and type:

for MD5:

```
    cd Downloads
    md5 ST-64bit-v1-0-2.dmg
```

oder for SHA-1

```
    shasum -a 1 ST-v2-0-0.dmg
```

## Create a checksum on Windows
You can use a tool like [HashCheck](https://github.com/gurnec/HashCheck/releases).

---------------

<div class="pageNavigation">
<div style="float:left;">
   [◀️ Home](index.md)
</div>
<div style="float:right;">
  [Installation ▶️](installation.md)
</div>
</div>
