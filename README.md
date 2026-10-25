# RPN ROM bank

A fallback copy of the HP calculator ROM packages that the RPN apps
(RPN 48, RPN 49G, RPN 50g) download.  The apps fetch them from
[hpcalc.org](https://www.hpcalc.org) and come here only when hpcalc.org does
not answer or serves a different file; either way the download must match the
SHA-256 below.

The files are attached to the [v1 release](https://github.com/gpasa/rpn-roms/releases/tag/v1),
byte for byte as published on hpcalc.org.

| File | Calculator | Source on hpcalc.org | Bytes | SHA-256 |
|---|---|---|---|---|
| `gxrom-r.zip` | HP 48GX, ROM R | `hp48/pc/emulators/gxrom-r.zip` | 321470 | `fa2d5704477926a5f41f638121f4f56903ae4dd984399257831097d90c874183` |
| `gxrom-p.zip` | HP 48GX, ROM P | `hp48/pc/emulators/gxrom-p.zip` | 321219 | `2ba77c5733aeae9048a43911917ca045e233699ccf7c29a544035dee428e44a4` |
| `sxrom-j.zip` | HP 48SX, ROM J | `hp48/pc/emulators/sxrom-j.zip` | 186908 | `09bd88d07eb0ebc4e4eade61c9f67d4f78b0b9d0b9e2feec818e1917a0807435` |
| `sxrom-e.zip` | HP 48SX, ROM E | `hp48/pc/emulators/sxrom-e.zip` | 183929 | `2aae7796def08ec18bdf94ca0b36912936eb9b990c22e048b1962a4799589c35` |
| `beta1196.zip` | HP 49G, ROM 1.19-6 | `hp49/pc/rom/beta1196.zip` | 1150781 | `df7314f9f665fd2e86160828291b48051a76d9c24ee7b23ff270af79139a4150` |
| `hp4950v215.zip` | HP 49g+/50g, ROM 2.15 | `hp49/pc/rom/hp4950v215.zip` | 1722704 | `ef95fcff19c27b155e0f4560e63241061b8f1778be64b46578b1798b65d37210` |
| `hp4950v210.zip` | HP 49g+/50g, ROM 2.10 | `hp49/pc/rom/hp4950v210.zip` | 2420234 | `567e3dd35eb535bb9b4f374bd043407ec5827beabd556c3b1506726432157e0f` |
| `hp49gp209.zip` | HP 49g+/50g, ROM 2.09 | `hp49/pc/rom/hp49gp209.zip` | 794234 | `0baf05508cf6ab68e402f81d257c5999ddeaa7ed9d44956f2964803487ead8f0` |

`SHA256SUMS` holds the same list for `shasum -a 256 -c`.

## Rights

The ROMs are Hewlett-Packard's software, copyright HP.  Since 2000 HP has
allowed the 38G, 39G, 40G, 48 and 49 ROMs to be used with emulators by people
who do not own the calculator, and HP published the 49g+/50g ROM updates
itself as free downloads.  Only ROMs that HP released this way belong here: no
ROM dumped from a calculator HP never released (HP-42S, 32S, 17B... and the
like) will ever be added.

This repository is not affiliated with HP Inc.  If you represent HP and want
a file removed, open an issue and it will be taken down.
