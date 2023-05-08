# V2ray Configuration : نصب کانفیگ و تونل زدن در وی تو ری

#### تونل زدن بین دوتا وی پی اس، ایرانی و اروپایی برای دور زدن نت ملی با کانفیگ V2Ray.


#### لینک ویدیو :
```
https://youtu.be/yoeCPO3qep8
```

###### احتیاج به دوتا سرور داریم، یکی ایران و یکی اروپا، برای خرید سرور اروپایی میتونید از لینک زیر استفاده کنید، توی ورود بهتون 200 دلار اعتبار میده.
```
https://m.do.co/c/0fb522deafa4
```

###### خرید دامنه از نیم چیپ: 
```
https://namecheap.pxf.io/BX7m6W
```
###### خرید دامنه سایت ایرانی: 
```
https://dashboard.azaronline.com/order/?aff=790&p=domain
```
###### خرید سرور از سایت ایرانی : 
```
https://dashboard.azaronline.com/order/?aff=790&p=vps
```

**If you think this project is helpful to you, you may wish to give a** 🌟

**Feel Free To Donation :** ❤️

>TRC20: ```TGTyqv2MH7dZztMvaP5PKuS9Bma8RY5Pk8```

>ETH: ```0x5b5202a54e5ce4fb25f0d886254eeb07bb088614```


###### روی سرور اروپایی وی پی ان رو ست میکنیم و روی سرور ایرانی آی پی فورواردینگ.



#### IRAN SECTION

```
apt-get update -y && apt-get upgrade -y
```

###### اگه با کد بالا مشکل داشتید و ارور گرفتید کد زیر رو ران کنید؛

```
apt update && apt upgrade -y
```
```
sysctl net.ipv4.ip_forward=1
iptables -t nat -A PREROUTING -p tcp --dport 22 -j DNAT --to-destination IRAN-IP
iptables -t nat -A PREROUTING -j DNAT --to-destination EU-IP
iptables -t nat -A POSTROUTING -j MASQUERADE
```

###### درصورتی که افت سرعت داشتید یا قطعی مکرر داشتید این کدو ران کنید

```
wget -N --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod +x bbr.sh && bash bbr.sh
```

#### EU SECTION

```
apt-get update -y && apt-get upgrade -y
```
```
apt install curl -y
```
```
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)
```

###### تا جایی پیش میریم که یه پیام چینی میاد و یه سوال بله خیر میپرسه، خیر رو میزنیم وکارمون تمومه با سرور اروپایی


###### آدرس پنل مدیریت
```
EU-IP:54321
```


###### یوزر و پسورد در حالت پیش فرض، حتما بعد از ورود پورت و یوزر و پسورد رو عوض کنید. 
```
admin, admin
```


###### درصورتی که افت سرعت داشتید یا قطعی مکرر داشتید این کدو ران کنید

```
wget -N --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod +x bbr.sh && bash bbr.sh
```


###### فایلایی که برای استفاده نیازه، توی آپلود سنتر ایرانیه.


###### برای ویندوز:
```
https://www.uplooder.net/files/b499308546bb1b4246663f86f9821f80/Windows.zip.html
```
###### برای اندروید:
```
https://www.uplooder.net/files/ae41f8c920d25903ec8c1ef7a185e141/Android.zip.html
```
###### برای آی او اس:
```
https://www.uplooder.net/files/18264dd47e1c7468e8e8e02357956a58/IOS---Mac.zip.html
```
