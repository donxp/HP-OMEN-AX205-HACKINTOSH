# Information
This is based on the work of XStar-Dev [here](https://github.com/XStar-Dev/HP_OMEN-2Pro_Hackintosh)

This config was used on macOS Catalina 10.15.5 with OpenCore 0.5.9.

# Laptop specifications
| Hardware | Model |
| ----- | ------ |
| BIOS | HP 8259 |
| CPU | Intel i7 7700hq |
| RAM | 8GB DDR4-2400 |
| SSD 1 | 128gb M.2 SSD |
| SSD 2 | SanDisk 500gb |
| iGPU | Intel HD 630 |
| dGPU | NVidia GeForce GTX 1050 (doesn't work) |
| WiFi | Intel 7265 AC (doesn't work) |

# What works
- Integrated graphics
- Keyboard & Touchpad (even with gestures)
- Brightness adjustment
- Audio + Audio keys
- Media keys (Play/pause etc)
- Ethernet
- Sleep & Wake with lid close
- Webcam

# What doesn't work
- The default WiFi chip does not function. There is ongoing work on community made drivers [here](https://github.com/AppleIntelWifi/adapter) however I could not get them to work.
- Once in the blue moon it kernel panics with graphical artifacts (still tracking this one down).
- CPU Power management & frequency does need some work (custom DSDT dump might fix this).
- No dedicated GPU on Catalina.

# What I didn't test
- Multi displays