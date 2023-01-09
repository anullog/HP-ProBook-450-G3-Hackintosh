# HP-ProBook-450-G3-OpenCore

OpenCore setup for running Hackintosh on HP ProBook 450 G3

### Laptop Specifications:
- Intel Core i5 6200U CPU (Skylake)
- Intel HD 520 Graphics
- 8GB DDR4-2133MHz RAM
- 15.6 Full HD Display
- Synaptics PS2 TouchPad
- Intel Dual Band Wi-Fi and Bluetooth Card
- 2 USB 3.0 Ports, 2 USB 2.0 Ports
- HDMI Port
- SD Card Reader
- Kingston SSD disk A400 120GB (upgraded)

### BIOS Setup:
- Disable Fast Boot
- Disable Power On when AC Detected
- Disable Power On when Lid is Opened
- Disable Secure Boot
- Disable Legacy Boot
- Enable Turbo Boost
- Enable Hyperthreading
- Enable Multi Processor
- Enable VT-x
- Disable Wake on LAN
- Video Memory Size: 64MB
- Enable Runtime Power Management
- Disable Extended Idle Power States
- Enable Deep Sleep
- Disable Wake when Lid is Opened
- Disable Wake on USB
- Enable Power Control

### What works:
- macOS Catalina 10.15.7
- UEFI booting via OpenCore
- Built-in keyboard (with special function keys)
- Built-in trackpad (basic gestures)
- Brightness Control Hotkeys
- Audio Control Hotkeys
- HDMI Video and Audio
- Integrated Camera
- Native Wifi and Ethernet
- Bluetooth and AirDrop
- Native audio with AppleALC, including headphone
- Built-in mic
- Native power management
- Battery status
- USB 3.0 Ports
- Ethernet
- Audio on internal speaker and headphone
- Sleep and Wake

### What doesn't work:
- FingerPrint Reader
- SD Card Reader

#### Thanks to:
- https://dortania.github.io/OpenCore-Install-Guide/
