# XRPL-Paper-Wallet
Trustless XRPL Paper Wallet Generator / Transfer


## Use At Your Own Risk
This software is provided "as is", without warranty of any kind, express or implied. While every effort has been made to ensure the accuracy and functionality of this tool, the users are advised to use it at their own risk.

## No Liability
The author(s) or distributor(s) of this tool shall not be held liable for any damages, including but not limited to direct, indirect, incidental, consequential, or punitive damages, arising out of the use of, or inability to use, this software.

## No Guarantee of Accuracy
The author(s) do not guarantee the accuracy or reliability of the results obtained through the use of this tool. The software is intended for informational and educational purposes only, and should not be considered as financial advice.

## Responsibility of Use
Users are solely responsible for the safekeeping of their XRPL credentials (e.g., seed phrases) and for the outcomes of the transactions they perform using this tool. It is highly recommended to double-check all transaction details and understand the risks involved, especially when dealing with cryptocurrencies.

## Compliance with Laws
Users are responsible for ensuring that their use of this software complies with all relevant laws and regulations in their jurisdiction, including but not limited to those concerning financial transactions and cryptocurrencies.

## Modification of Terms
The author(s) reserve the right to change these terms at any time without prior notice. It is the responsibility of the user to stay informed about any changes to these terms.





## Donations
Accepting donations in XRP at the following address:
rQw1WxHsHDygHWYbkDpCtjNAcwagepMMx6

## Account Generator
  1. Save the account-generator.html file to your computer.
  2. Verify the SHA256 Checksum from any online tool (https://emn178.github.io/online-tools/sha256_checksum.html)
  3. SHA256 Checksum: 7742cb20ea083b849898cd2a551d6e142d856d2e021036bfa17babfbb162ffcd
  4. Disconnect Wifi/Ethernet, your computer should be completely offline!
  5. Double click the account-generator.html and it will open in default browser, to ensure no logging and extra privacy
  6. Strongly recommend using a private browser such as Incognito Mode on Google Chrome, to ensure no logging of forms
  7. Click Green Button - Generate Wallet - Your Address and Seed Phrase will been shown
  8. WRITE THIS SEED PHRASE DOWN ON PAPER AND MAKE COPIES!
  9. DO NOT PUT SEED PHRASE ONLINE OR SHARE THEM WITH ANYONE!
  10. YOU MUST HAVE SEED PHRASE TO TRANSFER XRP TO ANY OTHER ADDRESS!

## XRP Transfer Tool
  1. Save the transfer-xrp.html file to your computer.
  2. Verify the SHA256 Checksum from any online tool (https://emn178.github.io/online-tools/sha256_checksum.html)
  3. SHA256 Checksum: c4cab7a0b269830699bf9e2cf9d7462605e2ad0505d8af703621be3c7463a9d8
  4. Double click the transfer-xrp.html and it will open in default browser
  5. Strongly recommend using a private browser such as Incognito Mode on Google Chrome, to ensure no logging and extra privacy
  6. Strongly Recommend Using WSS:// (SECURED Websocket) and not WS:// since you are signing with your Seed Phrase
  7. Input Seed Phrase, Amount of XRP, Fee, Destination Address and Destination Tag
  8. If you are sending to an exchange, most likely they will require Destination Tag!
  9. Click Green Button - Transfer XRP
  10. The Transfer XRP button will turn color orange and button will be disabled until a Result is received
  11. An alert will pop up telling you if the transfer was successfully submitted
  12. Transfer XRP button will turn green if success and red if failed
  13. If the XRPL starts being bogged down with network traffic:
    a. Go to xrpscan.com and get an idea of the average fee per ledger divided by number transactions
    b. Increase the fee in the transfer-xrp.html tool to meet the average or maybe slightly higher so your transaction will execute

## XRP Transfer Tool Testnet - Testing Tool
  1. You don't need to use this, it was simple to ensure transfer-xrp.html would work correctly
  2. There is some commented code such as await api.fundWallet(wallet); which you can use to fund your wallet on the testnet