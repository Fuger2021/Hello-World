# 练习1-必要开发工具
2022/05/11

**目录**
- [SSH](#ssh)
- [git](#git)
---

> <h2 id='ssh'>SSH</h2>
我的电脑以前配过一个密钥对，直接拿来用了

### WIndows
自带OpenSSH

### Linux
直接连虚拟机，连不上，重新配置
```bash
sudo apt-get install openssh-server openssh-client
service ssh restart
```
设置NAT模式，成功连接，但是我在Ubuntu里没找到.ssh文件夹，就手动建了一个，并上传公钥，因此这里没有要求密码
![img](https://github.com/Fuger2021/Hello-World/raw/master/img/p1.jpg)

> <h2 id='git'>git</h2>
截图是后面又push了一次传上去的
![img](https://github.com/Fuger2021/Hello-World/raw/master/img/p2.jpg)
