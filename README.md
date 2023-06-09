# KWiJisho

Fun and friendly interactive Discord bot with a wide range of functions, including a custom dictionary feature.

![image](https://github.com/monambike/kwijisho-discord-bot-legacy/assets/35270174/92857e80-9cbc-4422-b96f-b2d3d94a121e)

You can check the new version of this project written with C# [here](https://github.com/monambike/kwijisho-discord-bot).

## How to Edit the Bot

#### Notice: The following explanation will contain instructions on how to create a bot. It will simply provide information on what is needed to fetch and edit my bot.

After downloading the files, follow these steps:

1. Create a folder called `storage`.

2. Within this folder, create two files named `dictionaryFile.json` and `metaData.json`, and **place the following code inside both files**:

`storage\dictionaryFile.json`
```
{
    "Words": {
        "0": {
            "word": "",
            "desc": ""
        }
    }
}
```

`storage\metaData.json`
```
{
    "countOfWords": 0
}
```

3. Outside of this folder, at the root level, include a file named `config.json` with the following code:
```
{
	"prefix": "!",
	"token": "here-goes-the-token",
	"activity": "Ayaya!! Digite '!' para me chamar :D"
}
```
You will need to change the "token" field with the token of the bot you create. You can modify the "prefix" and "activity" of the bot as desired.

## Images

### See Words

![image](https://github.com/monambike/kwijisho-discord-bot-legacy/assets/35270174/ab8643cf-ac00-49f1-893c-9cb4039b5e6c)

### See Dictionary

![image](https://github.com/monambike/kwijisho-discord-bot-legacy/assets/35270174/4c0c9963-1b6c-4bb2-b6b2-c476ae4c12bc)

### Info

![image](https://github.com/monambike/kwijisho-discord-bot-legacy/assets/35270174/649c38ea-a3d6-4265-9d10-7632385f0df9)

### Help With Commands

![image](https://github.com/monambike/kwijisho-discord-bot-legacy/assets/35270174/e342e7f3-ceb0-4729-a01e-f95f5f9b732b)
![image](https://github.com/monambike/kwijisho-discord-bot-legacy/assets/35270174/ee4d1df7-e6aa-4c75-9a29-28694cb83fd8)
