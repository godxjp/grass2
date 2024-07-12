# Grass Auto Farm 

### What is bot for?
   - Farm Points
   - Check Points

## Quick Start 📚
   1. To install `pip install -r requirements.txt`.
   2. To start bot use `python main.py`.

### Options 📧
 - In `data/config.py` put `REGISTER_ACCOUNT_ONLY = False`
 - in `data/config.py`:
   - `APPROVE_EMAIL = False` approve email (Needed IMAP AND ACCESS to mail if TRUE)
   - `CONNECT_WALLET = False` connect wallet 
   - `SEND_WALLET_APPROVE_LINK_TO_EMAIL = False`  #send approve link to email
   - `APPROVE_WALLET_ON_EMAIL = False`  #get approve link from email (NEEDED IMAP AND ACCESS TO EMAIL)
   - `SINGLE_IMAP_ACCOUNT = False `  #if you have possibility to forward all approve mails to single IMAP address. 
   - `EMAIL_FOLDER = "" `  #skip for auto, folder where mails comes
   - `IMAP_DOMAIN = "" `  #skip for auto domain, not always works

### Configuration 📧

1. Accounts Setup 🔒
   Put in `data/accounts.txt` accounts in format email:password (godxjp@gmail.com:my_password123)

2. Proxy Setup 🔒
   Configure your proxies with the *ANY* (socks, http/s, ...) format in `data/proxies.txt` 🌐


