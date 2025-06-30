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
sudo useradd OPTION USER  // -p - пароль  
изменять юзеров можно через usermod  
  
// Логи  
journalctl -xe // просмотр всех логов  
journal --since "1 hour ago" // логи за последний час  


// настройка ssh  
sudo apt-get install openssh-server  
sudo apt-get install policycoreutils  
sudo apt-get install net-tools  
sestatus  
  
![image](https://github.com/user-attachments/assets/d03dccfd-7f93-4439-a4e8-5a2f2f9ef78b)  

ssh ip -p 2222  
  
// композиция рабочего стола:  
gsettings set org.gnome.desktop.interface enable-animations false  


