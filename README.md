# hexo-ruby-character #

Ruby charater tag for Hexo, inspired by the [Ruby templete](http://zh.moegirl.org/Template:Ruby) of [萌娘百科](http://zh.moegirl.org).

## Install ##

```
npm install hexo-ruby-character --save
```

## Usage ##

`{% ruby Base|top %}` → <ruby>Base<rp>（</rp><rt>top</rt><rp>）</rp></ruby>

Specifically, if the top field is in Chinese, it while be convert to pinyin, because the pinyin chatater with heads are not easy to type.

Following is the example.

`{% ruby 佐天泪子|掀群狂魔 %}`  → <ruby>佐天泪子<rp>（</rp><rt>xiān qún kuáng mó</rt><rp>）</rp></ruby>

Other language like Japanese is also supported.

`{% ruby 超電磁砲|レールガン %}` → <ruby>超電磁砲<rp>（</rp><rt>レールガン</rt><rp>）</rp></ruby>

## Known issues ##



