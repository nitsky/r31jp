r31jp_run
============

Setup
============

1. Buy a USB-Serial adapter, here's one I recommend:

    http://www.amazon.com/TRENDnet-RS-232-Serial-Converter-TU-S9/dp/B0007T27H8/ref=sr_1_1?ie=UTF8&qid=1372904367&sr=8-1&keywords=usb+serial

2. Install drivers:

    http://prolificusa.com/files/md_PL2303_MacOSX10.6_dmg_v1.4.0.zip

```
git clone git@github.com:nitsky/r31jp_run.git
cd r31jp_run
make
./r31jp_run -s path/to/serial/port path/to/code.asm
```

This project is released under the MIT License.

