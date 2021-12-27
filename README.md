# cwlwebapp.github.io

# https://www.itranslater.com/qa/details/2583147362529051648
# http://www.linuxfly.org/post/543/


可以通过下面的命令获得缓存中的DNS 结果：
```
ipconfig /displaydns
```
而下面的命令可以强制清除这些DNS 缓存：

```
ipconfig /flushdns
```
如果您觉得DNS Client服务带来麻烦，可以用在控制面板——服务 中停止，或使用下面的命令停止该服务：
```
net stop dnscache
```
重新启动该服务：
```
net start dnscache
```
