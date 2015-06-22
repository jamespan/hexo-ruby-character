# hexo-ruby-character #

[![npm](https://img.shields.io/npm/v/hexo-ruby-character.svg?style=plastic)](https://npmjs.org/package/hexo-ruby-character) [![npm](https://img.shields.io/npm/dm/hexo-ruby-character.svg?style=plastic)](https://npmjs.org/package/hexo-ruby-character)

Ruby character tag for Hexo, inspired by the [Ruby template](http://zh.moegirl.org/Template:Ruby) of [萌娘百科](http://zh.moegirl.org).

## Install ##

```
npm install hexo-ruby-character --save
```

## Usage ##

`{% ruby Base|top %}` → <ruby>Base<rp> (</rp><rt>top</rt><rp>) </rp></ruby>

Specifically, if the top field is in Chinese characters, it while be converted to Chinese pinyin, because the pinyin chatater with heads are not easy to type.

Followings are the examples.

`{% ruby 佐天泪子|掀裙狂魔 %}` → <ruby>佐天泪子<rp> (</rp><rt>xiān qún kuáng mó</rt><rp>) </rp></ruby>

Other languages like Japanese is also supported.

`{% ruby 超電磁砲|レールガン %}` → <ruby>超電磁砲<rp> (</rp><rt>レールガン</rt><rp>) </rp></ruby>

## Known issues ##



