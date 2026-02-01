```bash
bash <(curl -s https://pterodactyl-installer.se)
```
Wing Daemon Port
```8443```

```systemctl start wings```


```mkdir -p /etc/certs```


```cd /etc/certs```


```openssl req -new -newkey rsa:4096 -days 3650 -nodes -x509 -subj "/C=NA/ST=NA/L=NA/O=NA/CN=Generic SSL Certificate" -keyout privkey.pem -out fullchain.pem```


```bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/blueprint/main/blueprint-installer.sh)```


```bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/blueprint/main/addon-installer.sh)```


```bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/custom/main/custom)```


```bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/Docker/main/install)```


```mv fileName /var/www/pterodactyl```

```blueprint -remove name```

Simaple Ptero Panel Install
```bash <(curl -s https://ptero.jishnu.site)```
Wing Port ```443```
