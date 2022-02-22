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
debian 11，root密码MoeClub.org
``` bash
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/MoeClub/Note/master/InstallNET.sh') -d 11 -v 64
```

## warp
``` bash
bash <(curl -fsSL git.io/warp.sh) wg
```

## 国内三网测速
``` bash
bash <(curl -Lso- https://git.io/Jlkmw)
```

## 国内四网回程（寄了）
``` bash
wget -qO- git.io/autobesttrace | bash
```

## 探针
``` bash
wget https://raw.githubusercontent.com/cokemine/ServerStatus-Hotaru/master/status.sh && bash status.sh
```
若服务器位于中国大陆建议选择Coding.net仓库
``` bash
wget https://cokemine.coding.net/p/hotarunet/d/ServerStatus-Hotaru/git/raw/master/status.sh && bash status.sh
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

## PagerMaid-Modify
``` bash
wget https://raw.githubusercontent.com/Xtao-Labs/PagerMaid-Modify/master/install.sh -O install.sh && chmod +x install.sh && bash install.sh
```

## N1 openwrt在线升级
``` bash
bash <(curl -Lso- https://git.io/Phicomm-n1_update)
```
