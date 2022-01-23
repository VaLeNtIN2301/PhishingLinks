# Types of scams on Discord & how to handle them:
![Welcome to Policy at Discord!](https://images-ext-1.discordapp.net/external/wnhco0Jxc5iC7JHdZlW3ejzK-tn6EY19fejXMgTMyn4/https/miro.medium.com/max/1200/0%2AkF2QnaoPP31T5pxj?width=480&height=192)

**Consider putting a ⭐️ on this repo if you find it helpful!**

**What are phishing links?**

> Phishing domains (...)

![example of phishing DM](https://i.imgur.com/zS2EPAU.png?width=480&height=192)

**Other Types of Scams**

> text (...)

**Fake Community Programs Invitation**

> You were randomly selectected to join HypeSquad Events or your community has been selected for the Partner program without even applying?

![2nd example of phishing DM](https://images-ext-2.discordapp.net/external/tV1Dk9i7JAJNKWr_qinQ6jn5zZzU-PrFTxnD8EEwQQY/https/media.discordapp.net/attachments/870365789847429270/934302746667003925/unknown.png?width=931&height=664)

**title**

> text

**Loading Image Scam**

> Example

![screenshot](https://media.discordapp.net/attachments/888839159551258664/934896124496584804/unknown.png)

**title**

> text

**How to avoid them?**

> You can use auto-moderation systems that use known APIs to detect bad domains & phishing links. Here are some examples:
> 
> [CrossLink](https://discord.com/oauth2/authorize?client_id=742711687777484871&permissions=103348038854&scope=bot%20applications.commands), [SafeLink](https://discord.com/oauth2/authorize?client_id=819742627032596480&permissions=268725318&scope=bot+applications.commands), [AutoModerator](https://discord.com/oauth2/authorize?client_id=847081327950168104&permissions=83968&scope=applications.commands%20bot), [Dyno](discord.com/oauth2/authorize?client_id=161660517914509312&scope=bot%20identify%20guilds%20applications.commands&response_type=code&permissions=2134207679), [Waifu](https://discord.com/oauth2/authorize?client_id=434556304661544960&scope=bot+applications.commands&permissions=403041526), [🐟🐠](https://discord.com/oauth2/authorize?client_id=892420397570592768&scope=bot%20applications.commands&permissions=268446726)


**Invite Rewards Servers**

> Head to the discord developers portal and create a new application. Call it what you want and then navigate to the Bot tabb on the left side. Scroll down until you see two toggles under **Priviledged Gateway Intents**. Enable **Both** of the two toggles. once done, go to the left column and selct the **Oauth2** option. Where it says Redirects, input these four Redirects into seperate options. **http://localhost:1234 , http://localhost:1234/auth/oauth-callback , http://localhost:8800** and **http://localhost:8800/auth/oauth-callback**. If you have done things correctly, it should look like this: .

![example](https://i.imgur.com/YUhgkpt.png)

**Step 5**

> Now, youre ready to start getting the bot ready. open vscode back up and you should see a file with the name **.env.example** . click the new file button and name a new file **.env** . inside of here, paste this -> KEY="abcdefghijklmnopqrstuvwxy1234567" . Once this is done, open up the Dashboard folder. in here there will be another **.env.example** file. Just like before, create a new file called **.env** in the same place. inside of here, paste this -> API_URL="http://localhost:8800" . Brilliant, now for the second part. Open up the Backend folder and here you will see **bot.env.example** and **api.env.example** . just like the past two files, crate new ones, but this time you want to call them **bot.env** and **api.env** . for the bot.env and api.env files, look at the two images below to see what you need to put in them to make them work. the Token, client id and client secret can all be found on the discord developers portal. if you need any help, send a message in the zeppelin suppourt server and someone will be there to help you. Once youve done this, its time to move on.

![api.env](assets/image3.PNG)
![bot.env](assets/image4.PNG)

> Now its time to change 2 very important files. Firstly, go into the backend folder and find the file named **package.json** . Inside of here, you want to find the end oif **lines 10 and 13**. at the end of these lines it should say **index.js** . You want to change this to say **index.js init**. Secondly, You are wanting to go to the file Backend/src/data/db.ts . Inside of this file you want to remove everything so the is no code in there at all. then you want to replace it with the code pasted here -> (https://github.com/Dragory/ZeppelinBot/blob/6a3007562ebd802d01410bf68eda875d6d3a5837/backend/src/data/db.ts). Once these two changes have been made, the bot is ready to run.

**Malware & Token Stealers**

> You were randomly selectected
> 
![example](https://i.imgur.com/L9dl5Y1.png)


**Step 8**

> text

**How to Properly Report Issues to Trust & Safety**

> text

**How Discord is Fighting Spam**
> ”You know it. We know it. Spam sucks. So today, we want to tell you what we are doing to combat it.””

https://discord.com/blog/how-discord-is-fighting-spam
![How Discord is Fighting Spam](https://images-ext-2.discordapp.net/external/MJqE8I4deOWknsrajka6-BsdPFb6mvK9zsHvUms_ApQ/https/assets-global.website-files.com/5f9072399b2640f14d6a2bf4/618db6b2cf98f2d9aa324a53_image5.png?width=960&height=384)

**text**
