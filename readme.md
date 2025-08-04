# Telegram AutoPost Bot (Python)

Bot, belirli aralıklarla Telegram kanalına/grubuna otomatik mesaj gönderir,  
eski mesajları siler, admin kontrolü sağlar.

## Ortam Değişkenleri

- BOT_TOKEN: Bot token (BotFather’dan alınır)  
- ADMIN_ID: Admin Telegram kullanıcı ID’si  

## Komutlar

- /setchannel @kanaladi  
- /setinterval dakika  
- /setdays gün_sayisi  
- /addpost mesaj  
- /removepost mesaj_no  
- /startposting  
- /stopposting  

## Çalıştırma

```bash
pip install -r requirements.txt
python bot.py

---

## Senin için GitHub’a Yükleme Adımları

1. Bu dosyaları `telegram-autopost-bot` adlı klasöre koy.
2. Terminalde klasöre gel:
```bash
git init -b main
git add .
git commit -m "Python Telegram autopost bot"
