r31jp
============

1. Buy a USB-Serial adapter, here's one I recommend:

    http://www.amazon.com/TRENDnet-RS-232-Serial-Converter-TU-S9/dp/B0007T27H8/ref=sr_1_1?ie=UTF8&qid=1372904367&sr=8-1&keywords=usb+serial

2. Install drivers:

    http://prolificusa.com/files/md_PL2303_MacOSX10.6_dmg_v1.4.0.zip

3. Install python and pip, then install pySerial

```
pip install pyserial
```

4. Install r31jp:

```
brew tap nitsky/r31jp
brew install r31jp
```

5. Build and run!

```
r31jp path/to/code.asm
```

or specify a serial port:

```
r31jp -s path/to/serial/port path/to/code.asm
```

This project is released under the MIT License.
