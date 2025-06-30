# demoex
// приложения  
sudo apt install ark  
sudo snap install paintsupreme-3d  
sudo apt install -y clamav clamtk // антивирус  
sudo apt install cpu-x  
sudo apt install gnome-system-tools // группы пользователей  
sudo snap install rider --classic // IDE  

// устанавливаем бд  
usdo apt update  
sudo apt install postgresql postgresql-contrib  
service postgresql  
  
// резервное копирование  
tar cvpzf backup.tgz –exclude=/proc –exclude=/lost+found –exclude=/backup.tgz –exclude=/mnt –exclude=/sys –exclude=/web /  *для сохранения ос  
  
// Настройка принтера  
sudo netstat -tupnl  
sudo apt install cups-pdf  
sudo /etc/init.d/cups restart  
sudo lpstat -p -d  
  
// Группы и пользователи  
sudo groupadd OPTION GROUP  
cat /etc/group  
sudo usermod -aG developers superuser1  
sudo useradd OPTION USER  
