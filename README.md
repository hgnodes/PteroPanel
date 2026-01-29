```bash
bash <(curl -s https://pterodactyl-installer.se)
```
Wing Daemon Port
```8443```

```systemctl start wings```


```mkdir -p /etc/certs```


```cd /etc/certs```


```openssl req -new -newkey rsa:4096 -days 3650 -nodes -x509 -subj "/C=NA/ST=NA/L=NA/O=NA/CN=Generic SSL Certificate" -keyout privkey.pem -out fullchain.pem```
