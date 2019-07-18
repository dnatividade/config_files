## Debian 10 (Buster)
```
deb http://deb.debian.org/debian/ buster main
deb http://security.debian.org/ buster/updates main
```
---

## Debian 9 (Stretch)
```
deb http://deb.debian.org/debian/ stretch main
deb http://security.debian.org/ stretch/updates main
```
---

## Debian 8 (Jessie)
```
deb http://deb.debian.org/debian/ jessie main
deb http://security.debian.org/ jessie/updates main
```

#### Add this line in /etc/apt/apt.conf (create it if it doesn't already exist):
```
Acquire::Check-Valid-Until false;
```
---

## Debian 7 (Wheezy)
```
deb http://archive.debian.org/debian wheezy main
```
---

## Debian 6 (Squeeze)
```
deb http://archive.debian.org/debian squeeze main
deb http://archive.debian.org/debian squeeze-lts main
```
---

#### Add this line in /etc/apt/apt.conf (create it if it doesn't already exist):
```
Acquire::Check-Valid-Until false;
```
---

## Debian 5 (Lenny)
```
deb http://archive.debian.org/debian-archive/debian/ lenny main contrib non-free
deb http://archive.debian.org/debian-security/ lenny/updates main contrib non-free
```
---

## Debian 4 (Etch)
```

```
---

