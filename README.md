# 🎉 Docker Pure-FTPd

Pure-FTPd is actively supported, and it was always designed with security in mind, and the code is always re-audited as new kind of vulnerabilities are discussed.
The server can run with privilege separation for paranoid security. It can even run 100% non-root, with its built-in chroot() emulation and virtual accounts.
Transmission of cleartext passwords and commands can be avoided : Pure-FTPd has optional support for an SSL/TLS encryption layer using the OpenSSL library.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🥈 FTP

```shell
ftp://localhost/ username : `admin` password : `admin`
```

### 🥈 Run

```shell
docker-compose up -d
```
