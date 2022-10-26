---
description: Instructions to setup the bot
---

# 🖥 How to setup the bot

Download the bot and configuration files (configfile.py and dex.json)

FOR WINDOWS ONLY

Make sure that the name of the configfile file is configfile.py

If you can't see the file extensions like this:

<figure><img src="../.gitbook/assets/file list.jpg" alt=""><figcaption><p>FILES MUST NOT APPEAR LIKE THIS</p></figcaption></figure>

&#x20;follow these link:&#x20;

{% embed url="https://vtcri.kayako.com/article/296-view-file-extensions-windows-10" %}

After this, files will be like this:

<figure><img src="../.gitbook/assets/correct.jpg" alt=""><figcaption><p>FILES MUST APPEAR LIKE THIS</p></figcaption></figure>

Make sure filenames don't have spaces or other characters like that.

<figure><img src="../.gitbook/assets/errornamefile.jpg" alt=""><figcaption></figcaption></figure>

Open the configfile with a text editor (I suggest visual studio code or a normal text editor is okay too) and go to the bottom of the file

<figure><img src="../.gitbook/assets/wallets.png" alt=""><figcaption><p>Bottom of the copnfigfile</p></figcaption></figure>

This is an array of wallets.

The first one must be the one that hold our token AVID2.0 ("Public", "private")

Replace PUBLIC with your public key and PRIVATE with your private key.

| Extract the private key from metamask                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                  Example |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------: |
| <p></p><ol><li>Click on the identicon in the top right.</li><li>Select the account you'd like to export.</li><li>On the account page, click on the menu (three dots) in the upper right corner, and then on the "Account Details" button.</li><li>Click “Export Private Key”.</li><li>To access your private key, you'll now need to enter your wallet password. Once you've done so, click “Confirm” to proceed.</li><li>Your private key will now be revealed. Click to copy it, and save it somewhere safe. (Note: we aren't showing it in the below screenshot for obvious reasons -- but yours will be there.)</li><li>Click “Done” to close the screen.</li></ol> | ![](../.gitbook/assets/How\_to\_export\_an\_account's\_private\_key.gif) |



<figure><img src="../.gitbook/assets/walletsfilled.png" alt=""><figcaption><p>3 wallets</p></figcaption></figure>

If you want to add one wallet only, just delete others lines

Remember that the first wallet must be the holder of the AVID2.0 Token

<figure><img src="../.gitbook/assets/onewalletsfilled.png" alt=""><figcaption><p>one wallet only</p></figcaption></figure>

Save the file and close it.

Dex file is provided with 20 different dexes so is ready to use.

To check how to add a DEX click [HERE](dex.json.md#dex)

To check how to add a TOKEN click [HERE](dex.json.md#coin)
