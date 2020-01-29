[ja](./README.ja.md)

# shell Error

　Perform error handling.

# Features

* function
* ligth red: `\e[91m`
* output to stderr: `1>&2`
* `$?` is `$BASH_LINENO`
    * When `$BASH_LINENO` is 0 (the number of lines divisible by 256), `$?` is set to 255

# Requirement

* <time datetime="2020-01-29T16:53:45+0900">2020-01-29</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspbian](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2019-09-26 <small>[setup](http://ytyaru.hatenablog.com/entry/2019/12/25/222222)</small>
* bash 5.0.3(1)-release

```sh
$ uname -a
Linux raspberrypi 4.19.75-v7l+ #1270 SMP Tue Sep 24 18:51:41 BST 2019 armv7l GNU/Linux
```

# Installation

```sh
git clone https://github.com/ytyaru/Shell.Error.20200129165348
```

# Usage

```sh
cd Shell.Error.20200129165348/src
. Error.sh
Throw 'Error message.'
```

# Author

ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# License

This software is CC0 licensed.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.en)

