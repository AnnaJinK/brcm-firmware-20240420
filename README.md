## Raspberry Pi OS brcm frimware file
2024-03-12 릴리즈에 포함된 브로드컴 펌웨어 입니다.  
Raspberry Pi Zero W/2W 에 RetroPie 설치시 Wi-Fi 스캔 및 연결 동장이 불가능한 경우 사용합니다.

```
git clone https://github.com/AnnaJinK/brcm-firmware-20240312.git
cd ~
sudo cp -r firmware-brcm/brcm/* /lib/firmware/brcm
```
