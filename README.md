# pmpkpe

### Note

This code was repackaged into a command line utility for easier use.  Since the original code doesn't have a license or instructions on modification I wanted to give credit here.

The original author that I forked from is [kantium](https://github.com/kantium) and the original code can be found [here](https://github.com/kantium/pmpkpe)

### Feature

Generate your Protonmail Private Key passphrase based on the KeySalt and MailBoxPassword

### How to get your passphrase

*note : if you have a unique password on Protonmail, switch to a double password authentification (ProtonMail > Settings > Account)*

1. Install node.js (https://nodejs.org/en/download/package-manager/)
2. Recover your KeySalt and PrivateKey (https://github.com/scastiel/protonmail-export)
3. Install pmpkpe

```
npm install pmpkpe -g
```
 
4. cd into the newly cloned directory

```
cd pmpkpe
```

5. Execute this program against your saved salt, mailbox password, and private key

```
pmpkpe -s ./salt.txt -m ./mailboxpassword.txt
```

*enjoy*



