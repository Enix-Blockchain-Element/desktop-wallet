# Enix Desktop Wallet

**Clone and run to see it in action.**

This is a desktop wallet for the [Enix](https://enix.ai/) project.

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/Enix-Blockchain-Element/desktop-wallet
# Go into the repository
**IF ERROR [ cb() never called! ] appears then within same directory - run [ sudo chown -R $(whoami) ~/.npm ]**
cd desktop-wallet
# Install dependencies
npm install
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## IF Error or not Syncing  (Mac)

Quit the program (assuming you copied this to applications foler) and then run 


/Applications/"Enix Wallet.app"/Contents/Resources/bin/macos/geth --ws --wsorigins "*" --wsaddr 127.0.0.1 --wsport 8549 --port 30307 --wsapi "admin,db,eth,net,miner,personal,web3" --networkid 418 --syncmode fast

If this fails to action, then reboot device and re-run above.

## Downloadable Wallet Excutables

- mac OSX https://github.com/Enix-Blockchain-Element/desktop-wallet/releases/download/v1.0.0/EnixWallet-V1.0.0-macOS.zip
- Linux https://github.com/Enix-Blockchain-Element/desktop-wallet/releases/download/v1.0.0/EnixWallet-V1.0.0-Linux.zip
- Windows https://github.com/Enix-Blockchain-Element/desktop-wallet/releases/download/v1.0.0/EnixWallet-V1.0.0-Windows.zip

## Web Wallet (MEW Clone) 

- Web Wallet : http://wallet.enix.ai

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[CC0 1.0 (Public Domain)](LICENSE.md)

## ENIX Wallet

OpenSource Enix Wallet
Terms of Notice
Last Updated on October 11, 2019

These terms of service (“Terms”) govern your use of the Enix Wallet as a standalone application  (the “Services”) offered by this github (“we”, “us” or “our”). By using the Services, you acknowledge that you have read, understand and agree to be bound by these Terms. If you do not agree to these Terms, you may not use the Services.

Eligibility. You represent and warrant to us that: (a) you are an individual, at least 18 years of age or older and have the capacity to enter into these Terms and (b) you shall not use the Services if you are prohibited by any applicable law, regulation, or rule from doing so, including those relating to embargoes, sanctioned countries and sanctioned individuals.

Modification. We reserve the right, in our sole discretion to modify these Terms at any time and in our sole discretion. If we change these Terms, we will post the revised Terms here, and such changes will be effective immediately upon that posting. You should therefore periodically review these Terms when accessing or using the Services. Each use of the Services constitutes your agreement to be bound by and comply with the then-current Terms. If at any time you no longer agree to be bound by or comply with these Terms, then you should stop accessing and using the Services.

Compliance with Law. You agree to use the Services only for lawful purposes and in compliance with all applicable laws.

Use of the Services.

4.1. Credentials. We do not access or store your public or private key(s), backup phrases or passwords or other identifying information about you (“Credentials”). You are solely responsible for managing and maintaining the security of your Credentials. If you lose your Credentials, we do not have the ability to recover your Credentials or assist you in retrieving your Credentials, and you may not be able to access your Grams. Please note that we do not collect any personal information about you through your use of the Services.

4.2. Transactions. In order to be completed, any Enix-transaction created using the Services must be validated and recorded in the Enix Blockchain ledger. We have no control over the Enix Blockchain network and therefore cannot ensure that any transaction details that you submit via the Services or Transactions will be validated and confirmed on the Enix Blockchain. The transactions you submit via the Services or Transactions may not be completed, or may be substantially delayed by the Enix Blockchain. We have no control over the Enix Blockchain and do not have the ability to facilitate any cancellation or modification requests to transactions you have submitted. A fee may be imposed on your transaction by the Enix Blockchain. We have no control over the amount or type of such fees.

No Warranties. YOUR USE OF THE SERVICES IS AT YOUR OWN RISK. THE SERVICES ARE PROVIDED ON AN “AS IS” AND “AS AVAILABLE” BASIS, WITHOUT ANY WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED. WE DO NOT MAKE AND WE HEREBY DISCLAIM, ANY WARRANTY OR REPRESENTATION WITH RESPECT TO THE COMPLETENESS, SECURITY, RELIABILITY, QUALITY, ACCURACY, AVAILABILITY, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF THE SERVICES. WITHOUT LIMITING THE FOREGOING, WE DO NOT REPRESENT OR WARRANT THAT THE SERVICES WILL BE ACCURATE, CONTINUOUS, ERROR-FREE, UNINTERRUPTED, OR TIMELY, OR THAT THE SERVICES ARE FREE OF VIRUSES OR OTHER HARMFUL COMPONENTS OR THAT THE SERVICES WILL OTHERWISE MEET YOUR NEEDS OR EXPECTATIONS. SOME JURISDICTIONS DO NOT ALLOW EXCLUSION OF WARRANTIES OR LIMITATIONS ON THE DURATION OF IMPLIED WARRANTIES, SO THE ABOVE DISCLAIMER MAY NOT APPLY TO YOU IN ITS ENTIRETY, BUT WILL APPLY TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW. OBLIGATIONS UNDER THESE TERMS ARE FOR THE BENEFIT OF YOU ONLY, AND NOT FOR THE BENEFIT OF ANY OTHER PERSON.

Limitation of Liability. TO THE MAXIMUM EXTENT PERMITTED BY LAW, IN NO EVENT WILL WALLET COLLABORATORS NOR ANY PERSON ASSOCIATED WITH THIS OPEN-SOURCE-DECENTRALISED BLOCKCHAIN BE LIABLE FOR: (A) ANY DAMAGES, or (B) ANY LOSS OF USE, LOST ENIX OR OTHER CURRENCIES, LOST DATA, FAILURE OF SECURITY MECHANISMS, INTERRUPTION OF BUSINESS, OR ANY INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY KIND (INCLUDING LOST PROFITS IF ANY CLAIMS), REGARDLESS OF THE FORM OF ACTION, WHETHER IN CONTRACT, TORT (INCLUDING NEGLIGENCE), STRICT LIABILITY OR OTHERWISE, EVEN IF INFORMED OF THE POSSIBILITY OF SUCH DAMAGES IN ADVANCE. NOTWITHSTANDING ANY OTHER PROVISION OF THESE TERMS, NEITHER COLLABORATORS NOR ANY PERSON ASSOCIATED WITH ENIX DECENTRALISED BLOCKCHAIN SHALL HAVE ANY LIABILITY UNDER THESE TERMS.

Indemnity. You agree to indemnify and hold us and or anyone associated with decentralised-development from any and all claims, damages, losses, costs or expenses, including without limitation, reasonable attorneys’ fees, arising out of or relating to: (a) your use of the Services or transactions or the use of the Services or transactions by a third party using your credentials, whether authorized or not; and (b) your breach of these Terms. This indemnity shall survive any termination or cancellation of these Terms.

Third-Party Services. In using the Services, you may view content or services provided by third parties (“Third-Party Services”), including links to web pages and services of such parties. By using Third-Party Services, you agree to the terms and conditions of the respective Third-Party Service. We are not responsible or liable for any loss or damage of any sort incurred as a result of your use of a Third-Party Service. USE OF THE ENIX BLOCKCHAIN IS AT YOUR OWN RISK. WE DO NOT MAKE AND WE HEREBY DISCLAIM, ANY WARRANTY OR REPRESENTATION WITH RESPECT TO THE COMPLETENESS, SECURITY, RELIABILITY, QUALITY, ACCURACY, AVAILABILITY, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF THE ENIX BLOCKCHAIN.

Taxes. You are responsible for determining what, if any, taxes apply to your use of the Services or Enix's. We are not responsible for determining whether taxes apply to any transactions you make using the Services or for collecting, reporting, withholding or remitting any taxes arising from any virtual currency transactions.

Miscellaneous. If any provision of these Terms is found to be invalid, unlawful, void or for any reason unenforceable, then that provision shall be deemed severable from these Terms and shall not affect the validity or enforceability of any remaining provisions. These Terms and the Privacy Policy represent the entire agreement between you and us relating to your right to access and use the Services and supersede any and all prior agreements and understandings, written or oral, between you and us with respect to such subject matter. No waiver by us of any breach or default by you under these Terms shall be deemed to be a waiver of any preceding or subsequent breach or default. Any waiver by us must be in writing signed by us. These Terms shall be binding on your successors, heirs and assigns. You may not assign or transfer any of your rights or obligations under these Terms without our prior written consent, which may be withheld in our sole discretion. We may assign rights or delegate duties under these Terms in our sole discretion. Nothing in these Terms is intended to, nor shall create any partnership, joint venture, agency, consultancy or trusteeship. You and we are independent contractors for purposes of these Terms. These Terms shall be governed by and construed under and pursuant to the laws of England and Wales. Any dispute arising out of or in connection with this contract, including any question regarding its existence, validity or termination, shall be referred to and finally resolved by arbitration under the LCIA Rules, which Rules are deemed to be incorporated by reference into this clause. The number of arbitrators shall be three. The seat, or legal place, of arbitration shall be Nevis, St Nevis. The language to be used in the arbitral proceedings shall be English.
