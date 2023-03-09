# ESP8266-Cloud-MQTT-by-Mosquitto-To-NodeRED

# Node_red_Linux

## Register Frist
* github https://github.com/
* ngrok https://dashboard.ngrok.com/login


## How to install Server

* Open Browser https://pve22.ipv9.me/
* Login User: iot Pass: xxxx

```
apt update
```

## install Tmux
```
apt install tmux -y
```
### tmux tutorial linux
* Ctrl+B D — Detach from the current session.
* Ctrl+B % — Split the window into two panes horizontally.
* Ctrl+B " — Split the window into two panes vertically.
* Ctrl+B Arrow Key (Left, Right, Up, Down) — Move between panes.
* Ctrl+B X — Close pane.
* Ctrl+B C — Create a new window.
* Ctrl+B N or P — Move to the next or previous window.
* Ctrl+B 0 (1,2...) — Move to a specific window by number.
* Ctrl+B : — Enter the command line to type commands. Tab completion is available.
* Ctrl+B ? — View all keybindings. Press Q to exit.
* Ctrl+B W — Open a panel to navigate across windows in multiple sessions.

## install ngrok
```
wget https://nextcloud.cpe.ipv9.me/s/YW9oskX3scwrDyt/download/ngrok-v3-stable-linux-amd64.tgz
tar xvfz ngrok-v3-stable-linux-amd64.tgz
ls -l
cp ngrok /usr/local/bin/
ngrok
ngrok diagnose
ngrok config add-authtoken xxxxxx
cat .config/ngrok/ngrok.yml
ngrok http 1880
```

## install Node Red
```
apt install build-essential git curl -y
bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)
```
### Node Red tutorial linux
* node-red-start : this starts the Node-RED service and displays its log output. Pressing Ctrl-C or closing the window does not stop the service; it keeps running in the background
* node-red-stop : this stops the Node-RED service
* node-red-restart : this stops and restarts the Node-RED service
* node-red-log : this displays the log output of the service

