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
        
