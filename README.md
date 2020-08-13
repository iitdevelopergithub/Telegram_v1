# Telegram-hack (TELEGRAM Scraping Software)

1.Telegram data Scraper
2.Create group
3.Send Bulk Massage 

# Using this Software you can Scrape all member data in any groups

# Setup API

Go to http://my.telegram.org and log in. Click on API development tools and fill the required fields. put app name you want & select other in platform Example : copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )

• How To Install $ pkg install -y git python

$ git clone https://github.com/iitdevelopergithub/IITDEVELOPER-Telegram.git

$ cd TeleGram-Scraper

$ chmod +x * && python3 setup.py

To Genrate User Data $ python3 scrapr.py

( members.csv is default if you changed name use it ) Send Bulk sms To Collected Data $ python3 smsbot.py members.csv

add users to your group $ python3 Addintogroup.py
