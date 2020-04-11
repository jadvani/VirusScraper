# VirusScrapper

Scrap current Covid-19 world situation from [Worldometers](https://www.worldometers.info/coronavirus/) or the Spanish Government Covid-19 official [website](https://covid19.isciii.es/) and send all the information obtained by email. 

## How to launch
1. Clone repository
2. Open VirusScrapper.ipynb with Google Colab or Jupyter notebook
3. Setup your Gmail Parameters. Change *** with your personal password and email.

    ```
    password = '***'
    msg['From'] = '***'	
    msg['To'] = '***'
    ```

4. Run code


## How to enable Third-Party Mail Clients in Gmail settings
Inside "MyAccount" > "Sign-in & security" > "Connected apps & sites" > "Allow less secure apps"

More info in https://www.arclab.com/en/kb/email/how-to-enable-imap-pop3-smtp-gmail-account.html
