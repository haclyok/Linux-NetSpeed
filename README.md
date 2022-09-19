# Linux-NetSpeed
BBR+BBR魔改+Lotsever(锐速)一键脚本 for Centos/Debian/Ubuntu
支持系统：CentOS 6+、Debian 8+、Ubuntu 14+。
运行以下命令安装
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh


**********以下内容是COPY原作者过来的***********
本脚本已不更新，推荐使用5.5以上内核自带的bbr速度最佳
- https://roov.org/2020/03/bbr-bbrplus-bbr2/
- 推荐使用该脚本：bash <(curl -Lso- https://git.io/kernel.sh)
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
