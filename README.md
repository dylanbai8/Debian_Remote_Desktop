### 小内存VPS快速安装LXDE桌面环境 (以下命令适用于 Debian Ubuntu)

---
---

#### 完整安装：
```
apt-get update -y

apt-get install lxde -y

apt-get install xrdp -y
```

#### 精简安装
```
apt-get update -y

apt-get install xorg -y

apt-get install lxde-core -y

apt-get install xrdp -y

```

接下来打开你家电脑的Windows远程桌面连接工具，输入VPS的ip，按下回车，就OK啦~

