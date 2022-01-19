# scripts
自用脚本集合：

流媒体测测试
bash <(curl -L -s check.unlock.media) 

warp
bash <(curl -fsSL git.io/warp.sh)

国内三网测速
bash <(curl -Lso- https://git.io/Jlkmw)

四网回程
wget -qO- git.io/autobesttrace | bash

探针
wget https://raw.githubusercontent.com/cokemine/ServerStatus-Hotaru/master/status.sh && bash status.sh

综合性能测试
curl -sL yabs.sh | bash

iptables转发
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/iptables-pf.sh && chmod +x iptables-pf.sh && bash iptables-pf.sh

屏蔽BT
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/ban_iptables.sh && chmod +x ban_iptables.sh && bash ban_iptables.sh banall
