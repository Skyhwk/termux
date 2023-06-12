
## Instalasi
Untuk instalasi php dan apache2. Buka termux, lalu run command ini:

```
pkg install git -y && cd ~/ && git clone https://github.com/Skyhwk/termux.git && cd ~/termux && bash setup && cd ~/ && rm -rf termux
```
## Test Instalasi
Cek versi php:
```
php -v
```

Untuk menguji apakah PHP bisa  dirunning. Buat file index.php:
```
echo "<?php phpinfo();?>" > storage/shared/htdocs/index.php
```

start server:
```
apachectl
```
