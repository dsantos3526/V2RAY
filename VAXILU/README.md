#V2ray

# Cara install :
* Setting Cloudflare Setting (DNS a Record & aktifkan gRPC di menu Network)
* Install X-UI :
https://github.com/vaxilu/x-ui
* Install SSL
```javascript
sudo apt update
sudo apt install -y nginx
```
install cerbot
```javascript
curl -o- https://raw.githubusercontent.com/vinyll/certbot-install/master/install.sh | bash
```
```
certbot --nginx
```

Save lokasi SSL
```javascript
/etc/letsencrypt/live/x-ui.gtgcomputer.my.id/fullchain.pem
/etc/letsencrypt/live/x-ui.gtgcomputer.my.id/privkey.pem
```
Setting sertifikat SSL di x-ui panel

Jangan lupa Allow firewall
```javascript
sudo ufw allow 443
sudo ufw allow 80
sudo ufw enable
```


Optional- menganti WEB
```javascript
rm -rf /var/www/html/*
apt install unzip
cd /var/www/html
wget https://templatemo.com/tm-zip-files-2020/templatemo_563_seo_dream.zip
unzip templatemo_563_seo_dream.zip
mv templatemo_563_seo_dream/* .
rm -rf templatemo_563_seo_dream
```


```javascript
```















# Preference:
* https://www.youtube.com/watch?v=qhlLDUBP_Ng
* https://github.com/vaxilu/x-ui/
* https://github.com/vinyll/certbot-install
