[فارسی](./Readmefa.md) [English](./Readme.md)
# For Freedom ✊🏻

## ⚠️**use [x-ui](https://github.com/0xb4dc0d3x/x-ui) instead**⚠️

create a vps on digitalocean or anyware access to unsonsored internet
run bellow commands
```
git clone https://github.com/0xb4dc0d3x/V.git
cd V
sudo bash setup.sh
```
-------------------------------------------
### Settings (Optional) ❗
There is no need to configure the server, everything is installed and run automatically, but if you want, you can define and choose a separate uuid and port.
To do this, type the following command
```
cat /proc/sys/kernel/random/uuid
```
In the output, it gives you a string of letters and numbers that you have to copy like this
`3b91b7f7-f75e-4436-9286-109000cb36d2`
After copying, go to `config` dir and then use the command

`cd config` to go to the config dir


`sudo nano config.json` to change and configure the server

Line 9 and line 14 are for port and uuid respectively, change them

Now shut down the server you created with the `docker stop v2ray_freedom` command and enter the `sudo bash setup.sh` command again to apply the settings

-------------------------------------------
## How to connect🌐

after run setup  can see vmess sharable link this in your cli
```
vmess://your-link
```

you can connect to your vmess with any client like


android: https://play.google.com/store/apps/details?id=com.v2ray.ang&hl=en&gl=US


iOS: https://apps.apple.com/us/app/napsternetv/id1629465476

Desktop: https://github.com/MatsuriDayo/nekoray/releases/latest
