

<h2 align="center">
    ──「 ғɪʟᴇ sᴛᴏʀᴇ ᴘʀᴏ 」──
</h2>

<p align="center">
  <img align="center" alt="count" src=https://github.com/otterai/otterai/blob/main/asuka.gif>
</p>


<details>
###<summary><b>More</b></summary>


**If you need any more modes in repo or If you find out any bugs, mention in [@PythonBotz](https://www.telegram.dog/pythonbotz)**

**Make sure to see [contributing.md](https://github.com/CodeXBotz/File-Sharing-Bot/blob/main/CONTRIBUTING.md) for instructions on contributing to the project!**



### Features
- Fully customisable.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 

##
### Installation

#### Deploy on Koyeb

The fastest way to deploy the application is to click the **Deploy to Koyeb** button below.


[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/otterai/file-share-v2&branch=koyeb&name=filesharingbot)


#### Deploy in your VPS
````bash
git clone https://github.com/otterai/file-share-v2
cd file-share-v2
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````
</details>

### Admin Commands

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/users - view bot statistics

/broadcast - broadcast any messages to bot users

/stats - checking your bot uptime
```
<details>
<summary><b><blockquote>Explore Variables Set-up</blockquote></b></summary> 
    
### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `APP_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `DATABASE_URL` Your mongo db url
* `DATABASE_NAME` Your mongo db session name
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot, use HTML and <a href='https://github.com/codexbotz/File-Sharing-Bot/blob/main/README.md#start_message'>fillings</a>
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `PROTECT_CONTENT` Optional: True if you need to prevent files from forwarding

### EXTRA VARIABLES
* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/otterai/file-share-v2/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False
* `BOT_STATS_TEXT` put your custom text for stats command, use HTML and <a href='https://github.com/otterai/file-share-v2/blob/main/README.md#custom_stats'>fillings</a>
* `USER_REPLY_TEXT` put your text to show when user sends any message, use HTML


### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

#### CUSTOM_STATS

* `{uptime}` - Bot Uptime

</details>
### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Our Support Group Members

### Licence
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  


##

   **Star this Repo if you Liked it ⭐⭐⭐**

