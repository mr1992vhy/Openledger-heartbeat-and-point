# Openledger-heartbeat-and-point

* go to Openledger site and signup 
link : https://testnet.openledger.xyz/?referral_code=qx4eqasmdq

* after create account copy wallet address
* ![image](https://github.com/user-attachments/assets/af03e3de-e194-4be7-a585-0d168c1ae74c)

# how to run on VPS
* login to your vps
* download binary and open it
```
git clone https://github.com/vonssy/OpenLedger-BOT.git
cd OpenLedger-BOT
```
* open new screen
```
screen -S openledger
```
* isntall python 3.12
```
apt install python3.12-venv
```
```
python3 -m venv path/to/venv
```
```
source path/to/venv/bin/activate
```
```
pip install -r requirements.txt #or pip3 install -r requirements.txt
```
* import your account(s)
* Note : YOU CAN ADD MULTI ACCOUNT
```
nano accounts.txt
```
* if you have Proxy add it by this command ( but if you don't , skip this part )
```
nano manual_proxy.txt
```
* run Bot
```
python bot.py #or python3 bot.py
```
after the run you must be see log like this : 
![image](https://github.com/user-attachments/assets/cb26917e-a9b1-4764-8dab-ad47338febb8)

⚠️ **Disclaimer**  
Please note: The use of this bot is entirely at your own risk. Any consequences, including account bans or restrictions resulting from improper use of this bot, are solely your responsibility. This bot assumes no liability for any issues that may arise for users. By using this bot, you agree to these terms.
