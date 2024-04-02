# MaTouch packages for SquareLine OBP


```

Version:    V1.0
Author:     Vincent
Create Date:    2024/4/2
Note:


```


# Intruduce

With OBP, add preset Makerfabs MaTouch series screens to SquareLine.

Supported devices:
- [MaTouch ESP32-S3 4inch](https://www.makerfabs.com/esp32-s3-parallel-tft-with-touch-4-inch.html)
- [MaTouch ESP32-S3 2.1inch Rotary](https://www.makerfabs.com/matouch-esp32-s3-rotary-ips-display-with-touch-2-1-st7701.html)


# Usage

Copy the Makerfabs folder to the SquareLine boards folder

The board package files should be copied to the following path:

- Windows: C:\Users\USERNAME\Documents\SquareLine\boards
- Linux:~/SquareLine/boards
- MacOS: Users\USERNAME\SquareLine\boards


OBP file structure:

```
SquareLine_Studio
└── boards
    └── your_board_name
        └── version (v1_0_0)
            ├── your_board.png
            ├── your_board.zip
            └── your_board.slb

```