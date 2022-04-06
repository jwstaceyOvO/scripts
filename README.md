# 自用脚本集合：

## 流媒体测测试
``` bash
bash <(curl -L -s check.unlock.media) 
```

## XrayR
``` bash
bash <(curl -Ls https://raw.githubusercontent.com/XrayR-project/XrayR-release/master/install.sh)
```

## 一键DD
debian 11，root密码
``` bash 
MoeClub.org
```
``` bash
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/MoeClub/Note/master/InstallNET.sh') -d 11 -v 64
```

## 国内三网测速
``` bash
bash <(curl -Lso- https://git.io/Jlkmw)
```

## 国内四网回程
``` bash
wget -qO- git.io/autobesttrace | bash
```

## 综合性能测试
``` bash
curl -sL yabs.sh | bash
```

## iptables转发
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/iptables-pf.sh && chmod +x iptables-pf.sh && bash iptables-pf.sh
```

## 屏蔽BT
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/ban_iptables.sh && chmod +x ban_iptables.sh && bash ban_iptables.sh banall
```

## N1 openwrt在线升级
``` bash
bash <(curl -Lso- https://git.io/Phicomm-n1_update)
```
