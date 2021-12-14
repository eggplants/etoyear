# `etoyear`

Show eto-year(十二支).

Ref: [Earthly_Branches - Wikipedia](https://en.wikipedia.org/wiki/Earthly_Branches)

## Install

```bash
wget https://raw.githubusercontent.com/eggplants/etoyear/master/etoyear

# local
chmod +x etoyear

# global
sudo install -m+x etoyear /usr/local/bin
```

## Usage

```shellsession
$ ./etoyear
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

## License

MIT
