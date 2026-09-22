# rish
## встановлення dhizuku termux
1. ```bash
   termux-setup-storage
pkg update -y && pkg install -y termux-api play-audio python-pip dos2unix
```

2. ```bash
mkdir -p ~/Rish && cp -a /storage/emulated/0/Download/Rish/. ~/Rish/ 2>/dev/null || cp -a /sdcard/Download/Rish/. ~/Rish/ && cd ~/Rish && dos2unix rish && bash rish
```
3. ```bash
   cd ~/Rish && bash rish
   ```
