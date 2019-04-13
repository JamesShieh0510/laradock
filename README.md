#教學文件

##Step 1:建置Docker環境

### Mac Developer
```
##Install Docker For Mac:
https://store.docker.com/editions/community/docker-ce-desktop-mac
```
### Ubuntu Developer
```
##Install Docker For Ubuntu:
sudo apt-get update
apt-cache policy docker-ce
sudo apt-get install -y docker-ce
sudo systemctl status docker
sudo usermod -aG docker ${USER}
su - ${USER}
id -nG
sudo usermod -aG docker username
```
### Windows Developer
```
#Install Docker For Windows:
https://www.virtualbox.org/wiki/Downloads #download VirtualBox
https://hub.docker.com/editions/community/docker-ce-desktop-windows
```
