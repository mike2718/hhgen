# 业余无线电台呼号批量生成shell(yash)脚本

生成尽量接近真实的业余台呼号，是[查询工具]的副产物

使用`/dev/urandom`来生成物理随机的字符

目前只能生成中国大陆的业余台呼号

用法：

```
    $ yash hhgen.yash
```
## 依赖

* [yash](https://yash.osdn.jp/)
* 有`/dev/urandom`的Linux
