`cd ~`

`git clone https://github.com/TJP507/Linux-MOTD`

`cd ./Linux-MOTD`

`cp ./99-Tylers-MOTD /etc/update-motd.d`

`chmod +x /etc/update-motd.d/99-Tylers-MOTD`

`sudo run-parts /etc/update-motd.d/`
