# 随机业余无线电台呼号生成yash脚本

使用`/dev/urandom`提供熵，生成模拟的业余无线电台呼号，是[国内业余无线电台呼号分区信息查询C源程序](https://github.com/mike2718/hh)的副产物。

生成的呼号可能包括真实and/or虚拟的呼号，可在呼叫的练习中使用。

目前只能生成中国大陆的业余台呼号。

用法：

```
    $ yash hhgen.yash
```
## 依赖

* [yash](https://yash.osdn.jp/)
* 有`/dev/urandom`的[GNU/Linux](https://en.wikipedia.org/wiki/Linux)

