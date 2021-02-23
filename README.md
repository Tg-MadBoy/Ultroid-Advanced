## Ultroid Advanced - UserBot
A stable pluggable Telegram userbot, based on Telethon.

<b><i>Note :- 
This is not the real repository, just made it with some changes for myself.....
For real repo, visit [HERE](https://github.com/TeamUltroid/Ultroid)</i></b>

## If you are using this repo for yourself, I don't take guaranttee for the errors and lags in your userbots. Better use the <b><i><u>[official one](https://github.com/TeamUltroid/Ultroid)</u></i></b>.

<p align="center">
  <img src="./resources/extras/logo_rdm.png" alt="Ultroid-Advanced">
</p>

[![Stars](https://img.shields.io/github/stars/madboy482/Ultroid-Advanced?style=social)](https://github.com/madboy482/Ultroid-Advanced/stargazers)
[![Forks](https://img.shields.io/github/forks/madboy482/Ultroid-Advanced?style=social)](https://github.com/madboy482/Ultroid-Advanced/fork)
[![Python Version](https://img.shields.io/badge/Python-v3.9-blue)](https://www.python.org/)
[![Contributors](https://img.shields.io/github/contributors/madboy482/Ultroid-Advanced)](https://github.com/madboy482/Ultroid-Advanced/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/madboy482/Ultroid-Advanced/blob/main/LICENSE)
[![Size](https://img.shields.io/github/repo-size/madboy482/Ultroid-Advanced)](https://github.com/madboy482/Ultroid-Advanced/)

<details>
<summary>More Info</summary>
<br>
  Documentation soon..  <br />
</details>

# Deploy 
- [Heroku](https://github.com/madboy482/Ultroid-Advanced#Deploy-to-Heroku)
- [Local Machine](https://github.com/madboy482/Ultroid-Advanced#Deploy-Locally)

## Deploy to Heroku
- Get your `API_ID` and `API_HASH` from [HERE](https://my.telegram.org/)    
- Get your `SESSION` from [HERE](https://repl.it/@TeamUltroid/UltroidStringSession#main.py).   
and click the below button!  <br />  

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2Fmadboy482%2FUltroid-Advanced&template=https%3A%2F%2Fgithub.com%2Fmadboy482%2FUltroid-Advanced)

## Deploy Locally
- Get your `API_ID` and `API_HASH` from [HERE](https://my.telegram.org/)
- Get your `REDIS_URI` and `REDIS_PASSWORD` from [HERE](https://redislabs.com), tutorial [here](./resources/extras/redistut.md).
- Clone the repository: <br />
`git clone https://github.com/madboy482/Ultroid-Advanced.git`
- Go to the cloned folder: <br />
`cd Ultroid`
- Create a virtual env:   <br />
`virtualenv -p /usr/bin/python3 venv`   
`. ./venv/bin/activate`
- Install the requirements:   <br />
`pip install -r requirements.txt`   
- Generate your `SESSION`:   
`bash sessiongen`
- Fill your details in a `.env` file, as given in [`.env.sample`](https://github.com/madboy482/Ultroid-Advanced/blob/main/.env.sample).    
(You can either edit and rename the file or make a new file.)
- Run the bot:   
`bash resources/startup/startup.sh`

Made with 💕 by [@TeamUltroid](https://t.me/TeamUltroid). <br />

# Credits
* [Lonami](https://github.com/LonamiWebs/) for [Telethon](https://github.com/LonamiWebs/Telethon)

