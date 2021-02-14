# 随机业余无线电台呼号生成shell(yash)脚本

使用`/dev/urandom`提供熵，生成尽量接近真实的业余无线电台呼号，是[国内业余无线电台呼号分区信息查询C源程序](https://github.com/mike2718/hh)的副产物。

可在呼叫的练习中使用。

目前只能生成中国大陆的业余台呼号。

用法：

```
    $ yash hhgen.yash
```
## 依赖

* [yash](https://yash.osdn.jp/)
* 有`/dev/urandom`的Linux

