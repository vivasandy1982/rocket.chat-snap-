# 1
snap官方快照安裝程序
＃
sudo snap install rocketchat-server

指令列<your-domain-name>更換成你的網域
#
sudo snap set rocketchat-server caddy-url=https://<your-domain-name>
#
sudo snap set rocketchat-server caddy=enable
#
sudo snap set rocketchat-server https=enable
#
sudo rocketchat-server.initcaddy

# 3
#If no errors where found is safe to restart rocket.chat and Caddy:
#如果沒有發現錯誤，可以安全地重新啟動rocket.chat和Caddy
#重啟rocketchat
sudo systemctl restart snap.rocketchat-server.rocketchat-server.service
#重啟caddy
sudo systemctl restart snap.rocketchat-server.rocketchat-caddy.service

#如果你沒有網域只單純想只用ip對外搭建只需要執行第一步驟即可
#搭建完之後 輸入你的ip後面加上:3000即可 不過搭建好之後基本只需要輸入ip就會顯示安裝響導的初始畫面
#無sll進入方式
#http://你的vps_ip:3000
#有ssl網域進入方式
#https://你的網域
#無sll有網域進入方式
#http://你的網域
#----------------------以上為官方版本快速基本搭建其餘細項設定可至官網說明瀏覽------------------------------------------


