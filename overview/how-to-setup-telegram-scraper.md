---
description: Guide to setup telegram scraper
---

# 🛠 How to setup Telegram Scraper

{% hint style="warning" %}
Before being able to use the Telegram scraper, you need to follow the following steps to create the necessary files.
{% endhint %}

Follow this tutorial on YouTube to obtain the required data:

{% embed url="https://www.youtube.com/watch?ab_channel=Bemro&v=8naENmP3rg4" %}
Obtain API hash and API id
{% endembed %}



Now you can fill in the tg\_config.json configuration file as shown in the following image.

\


<figure><img src="../.gitbook/assets/api development1.png" alt=""><figcaption><p>tg_config.json example</p></figcaption></figure>



{% hint style="info" %}
The phone number should have the international prefix.
{% endhint %}

{% hint style="danger" %}
Note that the channels must be setted to 0 when you run the session creator
{% endhint %}



You can run now the file named session\_creator in the bot folder

&#x20;A Terminal window will show up and you will receive a message on telegram with a 6 digit code

Enter the code in the terminal and press enter

{% hint style="danger" %}
If you have protected your telegram account with a password, you will need to enter it in the terminal
{% endhint %}

Check in the bot folder that the .session file is created.

<figure><img src="../.gitbook/assets/sessions.png" alt=""><figcaption><p>session files example</p></figcaption></figure>

This file must remain in the same folder as the bot when it is running

You can now use the telegram scraper in the bot



## MAC users

For MAC users the usual rule applies. all files (including the session\_creator file) must be placed in the HOME FOLDER. The rest of the procedure is identical
