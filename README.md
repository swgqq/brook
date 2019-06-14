# brook
Brook官方脚本搭建步骤：
sudo -i
cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
date -R
wget wget https://github.com/swgqq/brook/blob/master/brook
chmod +x brook
./brook
./brook server -l :1234 -p pass
重连SSH
screen -dmS brook ./brook server -l :1234 -p pass
