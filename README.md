

```
git clone https://github.com/luckman666/PortScan.git

cd PortScan

# 192.168.1.102 也可以填写域名 1200线程数，9秒timeout

# 用python3写的请用python3以上版本

python main.py -d 192.168.1.102 -t 1200 -w 9
```
### 说明

多线程高效的端口扫描器

**python版本：3.x**
运行命令`python main.py -h`
```python
-h			帮助
-d			输入的主机名
-p			设置常见的top50,100,1000端口或者自定义的端口列表，目前还没有支持自定义端口范围扫描（待             实现）
-t			设置扫描的线程数
-w			设置等待连接的最大秒数
-s			显示namp统计的最常用top50,100,1000端口
```
