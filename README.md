```bash
bash <(curl -s https://pterodactyl-installer.se)
```

# Get-SSL-at-localhost
In this repo you will come to know how to install SSL certificates in your localhost.

# Create a folder for the certificates
```bash
mkdir -p /etc/certs
```

# Get into the folder
```bash
cd /etc/certs
```

# OpenSSL Seld-Signed Certificate Command:
```bash
openssl req -new -newkey rsa:4096 -days 3650 -nodes -x509 -subj "/C=NA/ST=NA/L=NA/O=NA/CN=Generic SSL Certificate" -keyout privkey.pem -out fullchain.pem
```

Wing Tunnel Port

```bash
ipv4:8443
```

```bash
systemctl start wings
```


```bash
bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/blueprint/main/blueprint-installer.sh)
```


```bash
bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/blueprint/main/addon-installer.sh)
```


```bash
mv fileName /var/www/pterodactyl
```

```bash
blueprint -remove name
```



```bash
bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/custom/main/custom)
```


```bash
bash <(curl -fsSL https://raw.githubusercontent.com/hgnodes/Docker/main/install)
```

