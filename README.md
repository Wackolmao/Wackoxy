<div align='center'>
  
![Alt](static/assets/img/doge.jpg)
# GGB  Unblocker
Welcome to the official repository of GGB Unblocker, the web proxy designed exclusively for students. We take immense pride in providing you with an unparalleled proxy service that is unrivaled in speed, security, and reliability.
</div>

## Supported Sites
Our web proxy supports almost every site. Some popular working sites include:
- [Discord](https://discord.com)
- [Geforce Now](https://play.geforcenow.com)
- [GitHub](https://github.com)
- [Spotify](https://spotify.com)
- [Reddit](https://reddit.com)
- [TikTok](https://tiktok.com)
- [YouTube](https://youtube.com)
- [CrazyGames](https://crazygames.com)

### Link Hosting
Hosting we use is [Xentain Solutions Cheap Hosting Budget VPS!](https://billing.xentainsolutions.com/aff.php?aff=22):
- The VPS Budget Plan I prefer to use is the Budget-4 Plan
- It has:
- Intel Xeon CPU
- 4 GB RAM
- 65 GB Storage
- 2 vCore
- Unmetered Bandwidth
- For just 4$ USD per month!
(Exchange Rates apply)
### Local Deployment
```
git clone https://github.com/Wackolmao/Wackoxy                 # Clone the Wackoxy repository
sudo apt update                                               # Update the package list
sudo apt install nodejs npm screen -y                         # Install nodejs, npm, and screen
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash   # Install nvm
export NVM_DIR="$HOME/.nvm"                                   # Set NVM directory
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"               # Load nvm
nvm install node                                              # Install the latest version of node using nvm
nvm use 18.18.0                                               # Use node version 18.18.0 (assuming this version exists)
cd doge-unblocker                                             # Change to the doge-unblocker directory
npm install                                                   # Install node modules from package.json
screen                                                        # Start a screen session (user should press space to continue)
npm start                                                     # Start the npm script (user will then use Ctrl+a+d to detach from screen)
```
### To set it up in docker(hope you cloned the repository already)
```
sudo apt install docker.io docker-compose -y
cd proxy
docker build -t wackoxy-image .
docker run -p 8080:8080 wackoxy-image
``` 
### The Links
[Click Here](https://proxy.theggbofficial.org)
### This isn't my own creation this is just taken and lightly modified from
[DogeUnblocker](https://github.com/DogeNetwork/dogeunblocker)
