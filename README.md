# `etoyear`

Show eto-year(十二支).

Ref: [Earthly_Branches - Wikipedia](https://en.wikipedia.org/wiki/Earthly_Branches)

## Install

```bash
wget https://raw.githubusercontent.com/eggplants/etoyear/master/etoyear

# local
chmod +x etoyear

# global
sudo install etoyear /usr/local/bin
```

## Usage

```shellsession
$ etoyear
2019 🐗
2020 🐁
2021 🐄
2022 🐯
2023 🐇
2024 🐲
2025 🐍
2026 🐎
2027 🐏
2028 🐒
2029 🐔
2030 🐕
$ etoyear -k 1999 100
1999 卯
2000 辰
2001 巳
2002 午
2003 羊
2004 申
2005 酉
...
2096 辰
2097 巳
2098 午
```

## Help

```shellsession
$ etoyear -h
NAME:
    etoyear - show eto-year list

USAGE:
    etoyear [-hvk] <begin> <num>

VERSION:
    etoyear version 0.0.4
    Copyright (c) 2019-2021 haruna <github.com/eggplants>
    Released under the MIT License.

OPTION:
   -h, --help    : show help
   -v, --version : show version
   -k, --kanji   : show animal(s) in kanji
```

## License

MIT
