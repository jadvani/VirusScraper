# VirusScrapper

[![Resume Preview](https://github.com/jadvani/jadvani.github.io/blob/master/covid.jpg)]


Scrap current Covid-19 world situation from [Worldometers](https://www.worldometers.info/coronavirus/) or the Spanish Government Covid-19 official [website](https://covid19.isciii.es/), and send all the information obtained by email. 

## How to launch
1. Clone this repository.
2. Open VirusScrapper.ipynb using Jupyter Notebook or Google Colab. 
3. Setup your Gmail parameters. Change *** with your personal account information (sender email + correspondent password, receiver email).

    ```
    password = '***'
    msg['From'] = '***'	
    msg['To'] = '***'
    ```
4. Run the code!

## Remember to enable Third-Party Mail Clients in Gmail settings
Inside "MyAccount" > "Sign-in & security" > "Connected apps & sites" > "Allow less secure apps"

Mre info here: https://www.arclab.com/en/kb/email/how-to-enable-imap-pop3-smtp-gmail-account.html

Note: if you copy and paste all the code in a .py extension file, you can manage your cronjobs to run the script periodically. I currently do this using a Google Cloud VM Instance.
