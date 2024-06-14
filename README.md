
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

## Izumi-v3 a simple Multi device Whatsapp Bot   
### Setup 
1. Get Session
   <br>
<a href='https://izumi.maskser.me' target="_blank"><img alt='Session' src='https://img.shields.io/badge/Session-V3100000?style=for-the-badge&logo=render&logoColor=white&labelColor=black&color=black'/></a>

2. Fork This Repository
   <br>
<a href='https://github.com/sataniceypz/Izumi-V3/fork' target="_blank"><img alt='FORK' src='https://img.shields.io/badge/fork-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=black&color=black'/></a>

3. Create account on Heroku
   <br>
<a href='https://signup.heroku.com/' target="_blank"><img alt='Heroku' src='https://img.shields.io/badge/-Create-black?style=for-the-badge&logo=heroku&logoColor=white'/></a>

4. Deploy on Heroku
   <br>
<a href='https://izumi-deploy.vercel.app/' target="_blank"><img alt='Deploy' src='https://img.shields.io/badge/-Deploy-black?style=for-the-badge&logo=heroku&logoColor=white'/></a>

### For getting session in Indian number
1.  Termux
    <br>
<a href='https://www.mediafire.com/file/iogcejb8629yv63/base.apk/file' target="_blank"><img alt='Install Termux' src='https://img.shields.io/badge/Install Termux-V2100000?style=for-the-badge&logo=scan&logoColor=white&labelColor=black&color=black'/></a>

2. download termux and run the command
    ```
   pkg update && pkg install -y nodejs git && git clone https://github.com/mask-sir/izumi-qr.git && cd izumi-qr && npm install && node index.js
   ```
### RUN ON VPS/TERMUX

1. Install packages
   ```
   apt update && apt upgrade -y && pkg install wget openssl-tool proot -y && hash -r && wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Ubuntu/ubuntu.sh && bash ubuntu.sh
   apt update && apt upgrade
   apt install sudo
   sudo apt install ffmpeg
   sudo apt install imagemagick
   sudo apt install yarn
   sudo apt install git
   sudo apt install curl
   sudo apt -y remove nodejs
   curl -fsSl https://deb.nodesource.com/setup_lts.x | sudo bash - && sudo apt -y install nodejs
   ```
2. installation
   ```
   git clone https://github.com/sataniceypz/Izumi-v3
   cd Izumi-v3
4. Configuration
   ```
   echo "TERMUX = true
   SESSION_ID = izumi~NJrnzJyS
   PREFIX = .
   READ_MSG = false
   ALWAYS_ONLINE = false
   REJECT_CALL = false
   LOG_MSG = true
   SUDO = 917994489493
   AUTO_STATUS_VIEW = true" > config.env
   ```
- Start
  ```
  npm install
  npm start
  ```
- Stop
  ```
  pm2 delete izumi
    
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

#### THANKS TO
- [ Mask-Ser💗](https://github.com/mask-sir) <br>
