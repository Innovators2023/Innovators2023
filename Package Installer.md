------------------------------------------------------------------------------------------------------------------------------------

╔╗╔╗╔╗╔══╗╔═╗ ╔╗╔═══╗╔═══╗╔╗╔╗╔╗╔═══╗    
║║║║║║╚╣╠╝║║╚╗║║╚╗╔╗║║╔═╗║║║║║║║║╔═╗║    
║║║║║║ ║║ ║╔╗╚╝║ ║║║║║║ ║║║║║║║║║╚══╗    
║╚╝╚╝║ ║║ ║║╚╗║║ ║║║║║║ ║║║╚╝╚╝║╚══╗║    
╚╗╔╗╔╝╔╣╠╗║║ ║║║╔╝╚╝║║╚═╝║╚╗╔╗╔╝║╚═╝║    
 ╚╝╚╝ ╚══╝╚╝ ╚═╝╚═══╝╚═══╝ ╚╝╚╝ ╚═══╝   

 ![Windows](https://th.bing.com/th/id/OIP.N_VNAacU9Z4J_0e1HB6j5wHaG8?w=193&h=181&c=7&r=0&o=5&dpr=1.1&pid=1.7)


 To Install simply click on the link below, and then download the file! :)

 ----------------------------------------------------------------------------------------------------------------------------------
 
 [WINDOWS PKG INSTALLER LINK](https://drive.google.com/file/d/1yFYLrYrCMae0o60dHrZyzucEgG5Jsqz1/view?usp=sharing)                      

 
-----------------------------------------------------------------------------------------------------------------------------------


▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
██░████▄░▄██░▀██░██░██░█▄▀█▀▄████░▄▄░█░▄▄▀█▀▄▀█░█▀█░▄▄▀█░▄▄▄█░▄▄
██░█████░███░█░█░██░██░███░██████░▀▀░█░▀▀░█░█▀█░▄▀█░▀▀░█░█▄▀█░▄▄
██░▀▀░█▀░▀██░██▄░██▄▀▀▄█▀▄█▄▀████░████▄██▄██▄██▄█▄█▄██▄█▄▄▄▄█▄▄▄
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀

![linux](https://th.bing.com/th/id/OIP.5iEExkJq1RedmgMu7W7TdgHaHa?w=167&h=180&c=7&r=0&o=5&dpr=1.1&pid=1.7)


**INSTRUCTIONS:**

1. NAVIGATE TO HOME PAGE
2. ENTER CTRL + T TO OPEN UP TERMINAL
3. COPY AND PASTE THE SCRIPT UNDERNEATH -------- LINE BELOW
4. PASTE IT INTO THE TERMINAL
5. ENTER PASSWORD TO SUDO 
6. IF YOU RUN INTO ANY ERRORS PLEASE CONTACT THE IT TEAM

-------------------------------------------------------------------------------------------------------------------------------------
```bash
#!/bin/bash

# Update package lists
sudo apt update

# Install standard applications (Firefox, Blender, 7-Zip)
sudo apt install -y firefox blender p7zip-full

# Install Google Chrome
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb

# Install Zoom
wget https://zoom.us/client/latest/zoom_amd64.deb
sudo apt install ./zoom_amd64.deb

# Google Drive and OneDrive integration via Gnome Online Accounts
sudo apt install gnome-online-accounts

# Install third-party Onedrive Client
sudo apt install onedrive

# Install PeaZip
wget https://github.com/peazip/PeaZip/releases/download/8.6.0/peazip_8.6.0.LINUX.GTK2-2_amd64.deb
sudo apt install ./peazip_8.6.0.LINUX.GTK2-2_amd64.deb

# Install Dropbox
wget -O - "https://www.dropbox.com/download?plat=lnx.x86_64" | tar xzf -
~/.dropbox-dist/dropboxd

# Install Wine for WinSCP
sudo apt install wine
# Note: Manual step required to download and run WinSCP installer using Wine

echo "Installation completed."


