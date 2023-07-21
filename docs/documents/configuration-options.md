# How to config gitlab local server with self-signed certificate

## 1. Generate self-signed certificate

```bash
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout gitlab.key -out gitlab.crt
```
