---
description: Simple guide with examples to check methoids from the bot
---

# 🔍 Find mempool MethoId from the bot

{% hint style="warning" %}
The transactions for adding or removing liquidity (add Liquidity etc ...) are sent to the Router address.&#x20;

While enable trading transactions (TradingEnabled, EnableTrading etc ...) are sent to the token address.
{% endhint %}

The bot can scan either on the router address or on the token address.

Depending on the transaction you are looking for, you will need to select Trading enabled or addingliquidity. After that you will have to enter the methoids in the corresponding field.

## How to find MethoId from the bot

Paste the contract of the Token that you want to scan

<figure><img src="../.gitbook/assets/paste_token_address.png" alt=""><figcaption><p>Paste token address in the field</p></figcaption></figure>

Click on SIGNATURES label on the right, and than on FIND SIGN

<figure><img src="../.gitbook/assets/click_on_signatures_label.png" alt=""><figcaption><p>Click on SIGNATURES than on FIND SIGN</p></figcaption></figure>

A List of functions will be printed

<figure><img src="../.gitbook/assets/list_of_functions.png" alt=""><figcaption><p>List of all the functions available in the contract of the token</p></figcaption></figure>

Find the MethoId that you need and copy it

<div>

<figure><img src="../.gitbook/assets/find_the_function.png" alt=""><figcaption><p>Find it!</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/copy_the_methodId.png" alt=""><figcaption><p>And copy it!</p></figcaption></figure>

</div>

Now enable the Mempool Snipe selecting the METHOID LABEL

<div>

<figure><img src="../.gitbook/assets/enable_mempool_snipe_and_paste.png" alt=""><figcaption><p>Enable mempool snipe selecting the METHOID</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/set_as_many_you_want_to_check.png" alt=""><figcaption><p>Add as many Methoid you want to check</p></figcaption></figure>

</div>

Now start the bot and wait that it find the methoid in the mempool!



This works for TTSA as well
