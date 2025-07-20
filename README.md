 برای ابدیت سرور این دستور رو میزنیم
```
sudo apt update && sudo apt upgrade -y
```
اگه دستور درحال اجرا بود این دستور میزنین
```
kill id
```
تانل کردن سرور ایران
```
wget https://raw.githubusercontent.com/lokidv/wghelper/main/install.sh && chmod +x install.sh && ./install.sh
```
برای ویرایش سرویس
```
nano /etc/systemd/system/udp2raw-scan.service
```
چک کردن وضعیت سرویس
```
sudo systemctl status udp2raw-scan.service 
```
برای ریستارت کردن سرویس
```
sudo systemctl restart udp2raw-scan.service 
```
برای متوقف کردن سرویس
```
sudo systemctl stop udp2raw-scan.service 
```
برای حذف سرویس
```
sudo systemctl disable udp2raw-scan.service 
```
برای فعال سازی سرویس
```
sudo systemctl enable --now udp2raw-scan.service

```
