# HamoniKR GPG Keyring

하모니카 리눅스에서 필요한 gpg keying 배포를 위한 패키지

Maintainer: Kevin Kim <root@hamonikr.org>

# Install

```
$ wget -O - http://apt.hamonikr.org/hamonikr.key | sudo apt-key add -

$ echo "deb https://apt.hamonikr.org me main upstream" | sudo tee -a /etc/apt/sources.list.d/hamonikr.list

$ sudo apt update

$ sudo apt install hamonikr-packages-keyring
```

# Build

데비안 패키지를 생성하기 위하여 아래와 같이 명령을 실행하면 생성됩니다.

```
$ apt build
```

# License

GPL-3+
