
1. ابتدا بررسی نمایید آیا پایتون روی توزیع نصب است یا خیر:
```
sudo python3 --version
```
2. سپس برای امکان اضافه‌کردن مخازن شخصی باید بسته زیر را دانلود و نصب نمایید:
```bash
sudo apt install software-properties-common -y
```
3. در اولین مرحله مخزن شخصی پایتون رو در توزیع خود بارگزاری می‌نماییم:
```bash
sudo add-apt-repository ppa:deadsnakes/ppa
```
4. سپس لیست مخازن توزیع خود را آپدیت می‌نماییم:
```bash
sudo apt update
```
5. برای نصب پایتون حالا از دستور زیر استفاده نمایید:
```bash
sudo apt-get install python3.10 python3.10-ven python3.10-dev
```
پس از نصب لازم است که برای اطمینان از نصب و اطلاع از محل نصب آن، دستور زیر را وارد نمایید:
```bash
which python3.10
```
6. در گام اخر لازم است که در فایل local.conf دستورات زیر را نیز اضافه نمایید محیط مجازی که قرار است Devstack و سایر سرویس‌ها در آن اجرا شوند با پایتون۳.۱۰ ساخته شود:
```bash
PYTHON3_VERSION=3.10
PYTHON=/usr/bin/python3.10
```
