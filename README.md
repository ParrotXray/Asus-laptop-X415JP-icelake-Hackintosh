# Asus-laptop-X415JP-Hackintosh

## 🖥️Device
| Model | Asus Laptop X415JP |
|------------|-------------------------------|
| CPU | i5 1035G1(ice lake) |
| GPU | Intel UHD Garphics |
| RAM | 16GB |
| Audio | Realtek ALC256 |
| WIFI／Bluetooth | ~~RTL8821CE~~ --> DW1820A |
| BIOS Version | 303 |

## 📀System
<img src="https://is4-ssl.mzstatic.com/image/thumb/Purple124/v4/09/59/3d/09593d0e-188a-77eb-4c38-ca40bedd5cff/ProductPageIcon.png/460x0w.webp" height="32px"/> Big Sur 11.6.1

<img src="https://aux.iconspalace.com/uploads/imac-icon-256.png" height="30px"/>SMBIOS：MacBookPro16,2

<img src="https://raw.githubusercontent.com/acidanthera/OpenCorePkg/master/Docs/Logos/LogoApprox.svg" height="34px"/>OC：0.7.7

![alt text](Hackintosh-X415JP.jpg)

## 🛠️Setting BIOS
Advanced > Intel AES-NI：Disable

Advanced > SATA Configuration > SATA Mode Selection：AHCI

Boot > Fast Boot：Disable

Security > Secure Boot > Secure Boot Control：Disable

- CFG Lock：Disable,You need to use ControlMsrE2.efi or CFGLock.efi

                <key>Tools</key>
                <array>
                        <dict>
                                <key>Arguments</key>
                                <string>unlock</string>
                                <key>Auxiliary</key>
                                <true/>
                                <key>Comment</key>
                                <string></string>
                                <key>Enabled</key>
                                <true/>
                                <key>Name</key>
                                <string>ControlMsrE2</string>
                                <key>Path</key>
                                <string>ControlMsrE2.efi</string>
                                <key>RealPath</key>
                                <false/>
                                <key>TextMode</key>
                                <false/>
                        </dict>
                </array>
## 💡Device status
### Works：
- [x] Graphics
- [x] USB
- [x] Webcam
- [x] Brightness controls
- [x] Battery percentage
- [x] Sleep
- [x] TouchPad
- [x] WiFi
- [x] Speakers
- [x] Microphone
- [x] Bluetooth
### No Works：
- [ ] HDMI and HDMI Audio
### Unkown：
- [ ] Apple Services
