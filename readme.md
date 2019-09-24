# `etoyear` is...
the command to show eto-year(十二支) list  
SEE ALSO... [Earthly_Branches - Wikipedia](https://en.wikipedia.org/wiki/Earthly_Branches)
## INSTALL
```
    $ git clone github.com/eggplants/etoyear
    $ cd etoyear;chmod 755 etoyear
    $ mv ~/local/bin/
    $ export PATH="$PATH:~/local/bin/"
```
## USAGE
    - etoyear [option -h,-v,-k] 
    [year (should >0)(default:${DEFAULT_YEAR})] [num of displayline(s) (should >0)(default:${DEFAULT_LINE})]
         - `var ${DEFAULT_YEAR}` = `date+%Y`
         - `var ${DEFAULT_LINE}` = `12`
## EXAMPLE
```
    $ etoyear             # show list from this year to the next ${DEFAULT_LINE} years in emoji
    2019	🐗
    2020	🐁
    2021	🐄
    2022	🐯
    2023	🐇
    2024	🐲
    2025	🐍
    2026	🐎
    2027	🐏
    2028	🐒
    2029	🐔
    2030	🐕
    $ etoyear -k 1999 100 # show list from 1999 to the next 100 years in kanji
    1999	卯
    2000	辰
    2001	巳
    2002	午
    2003	羊
    2004	申
    2005	酉
    ...
    2096	辰
    2097	巳
    2098	午
```

## COPYLIGHT
    Copyright (c) 2019- haruna <github.com/eggplants>

## LISENCE
    Released under the MIT License.

## OPTION
```
   -h, --help    # show help
   -v, --version # show version
   -k, --kanji   # show animal(s) in kanji
```
