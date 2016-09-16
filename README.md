# use-the-Apache-ab-tool
用Apache ab工具测试网站性能

1.进入Apache/bin目录
```
$ cd E:/appserv/Apache2.2/bin
```
2.输入测试命令

```
ab -n1000 -c10 http://localhost:2015/
```
-n:总请求数

-c:并发数

