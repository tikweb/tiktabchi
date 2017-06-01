tikTabchi
<div dir="rtl">
ربات پیشرفته تبلیغاتی چی


* * *

## دستورات

برای مشاهده دستورات از دستور help استفاده کنید
/help
شما میتونید همه دستورات  را با ! یا # و یا / نیز وارد کنید

* * *

# نصب
ابتدا دستورات زیر را کامل و پشت سر هم وارد کنید و منتظر نصب بمانید اگر از شما سوال پرسیده شد y بزنید.
```sh

sudo apt-get install python-setuptools
sudo apt-get install python-pip
sudo apt-get install python-redis
sudo pip install pyTelegramBotAPI
sudo pip install pyTelegramBotAPI --upgrade
sudo apt-get update
sudo apt-get install python2.7
sudo pip install pytelegrambotapi py==1.4.29 pytest==2.7.2 requests==2.7.0 six==1.9.0 wheel==0.24.0

```
حالا پیش نیاز ها نصب شده اند و برای نصب خود ربات دستورات زیر را به ترتیب وارد کنید

```sh
cd $HOME
git clone https://github.com/tikweb/tiktabchi.git
cd tiktabchi && cd bot
screen python tabchi.py
```
حالا فایل tabchi.py را ویرایش کنید 
خط 18 توکن ربات
خط 31 و 39 و 47 و 59 هم ایدی Sudo
را قرار دهید

</div>

* * *
