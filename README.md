
# Teneo Bot
Teneo bot is a simple tool designed to automate the node interaction.
- Register Link : [Register](https://dashboard.teneo.pro/auth/signup)
- Use this reff code to get extra points : 
```bash
hWc9y
```
- Download Extension : [Extension](https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm)
## Buy Proxies
- Free Proxies Static Residental: 
1. [WebShare](https://www.webshare.io/?referral_code=ic9d4taithna)
2. [ProxyScrape](https://proxyscrape.com/)
3. [MonoSans](https://github.com/monosans/proxy-list)
- Paid Premium Static Residental:
1. [922proxy](https://www.922proxy.com/register?inviter_code=5a410671)
2. [Proxy-Cheap](https://app.proxy-cheap.com/r/OhWwGe)
3. [Infatica](https://dashboard.infatica.io/aff.php?aff=571)

# Attention Before Running Teneo Cli Version

I am not `responsible` for the possibility of an account being `banned`, due to running node in the CLI, because
Officially Teneo Node Beta does not provide an option for the CLI version, only with the Chrome extension. but `I
think` there is no reason to ban the account, because this is not cheating, I didn't change anything in the script
(Heartbeats 15 minutes, maximum teneo points 25, maximum points per day 2400)

## To checks system's vCPU cores, RAM, and SSD (disk) usage
```bash
curl -o system_info.sh https://raw.githubusercontent.com/CryptoAirdropHindi/Tools/refs/heads/main/system_info.sh && chmod +x system_info.sh && ./system_info.sh
```
## Features
- **Automated node interaction**

## Prerequisites
- [Node.js](https://nodejs.org/) (version 12 or higher)
Node.js install
```bash
curl -o install-node.sh https://raw.githubusercontent.com/CryptoAirdropHindi/Tools/refs/heads/main/install-node.sh && chmod +x install-node.sh &&  ./install-node.sh
```
new Create screen
```bash
screen -S teneo
```

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/CryptoAirdropHindi/teneo-bot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd teneo-bot
   ```
4. Install the necessary dependencies:
   ```bash
   npm install
   ```

## Usage

1. Set the `account.txt` and `proxy.txt (if you want to use proxy)` before running the script. Below how to setup this fie.
2. Configuration:
   Modify the `account.txt` file with your account info
```bash
nano account.txt
```
```
email1,password1
email2,password2
email3,password3
```
To save the file, press `control+X+Y.`

# Modify and set the `proxy.txt` file if you want to use proxy
```bash
nano proxy.txt
```
```
ip:port
username:password@ip:port
http://ip:port
http://username:password@ip:port
```
To save the file, press `control+X+Y.`

3. Run the script:
```bash
node index.js
```
Use `A` and `D` to move/change view to other accounts, `C` to stop the script.
# View logs
```bash
screen -r teneo
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Note
This script only for testing purpose, using this script might violates ToS and may get your account permanently banned.
