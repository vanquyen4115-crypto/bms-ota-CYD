# TOOL BMS ESP32 Web Flasher

Upload this folder to a GitHub Pages branch or repository.

Required structure:

```text
index.html
manifest.json
firmware/
  bootloader.bin
  partitions.bin
  boot_app0.bin
  BMS-Tool-w1.bin
```

Open the GitHub Pages URL with Chrome or Microsoft Edge, connect the ESP32 by USB, then press `INSTALL TOOL BMS`.

The ESP32 offsets are:

```text
0x1000   bootloader.bin
0x8000   partitions.bin
0xE000   boot_app0.bin
0x10000  BMS-Tool-w1.bin
```
