# 随机业余无线电台呼号生成yash脚本

使用`/dev/urandom`提供的熵生成模拟的业余无线电台呼号，是[国内业余无线电台呼号分区信息查询C源程序](https://github.com/mike2718/hhcx)的副产物。

默认生成10组模拟的呼号，可在呼叫的练习中使用。

目前只能生成中国大陆的业余台呼号。

用法：

```bash
mike@DELL-PC:~/dev2/hhgen$ yash hhgen.yash

5位呼号 6位呼号
_____   ______
BK6JM   BA5WYE
BH0IU   BK0CBX
BC9UC   BG0HIR
BF8OO   BB7XXF
BL5VW   BF0HTP
BC2ER   BR4BUD
BA6AA   BA5NVE
BR5QR   BL2VGG
BI9GH   BI3KXK
BR2MJ   BA4TIM

```
## 依赖

* [yash](https://yash.osdn.jp/)
* 有`/dev/urandom`的[GNU/Linux](https://en.wikipedia.org/wiki/Linux)

