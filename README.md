Omegle to IRC
=============

This is an irc bot that allows communication with strangers on Omegle.

I made it to get acquainted with Twisted.

### Install  
First you need to install python and then the source dependencies
```
sudo apt-get install python
git clone https://github.com/simon-weber/omegle-to-irc.git
cd omegle-to-irc
pip install -r requirements.txt
```
 
Then run with  
`python bridge.py`  


### Commands 
Automatically connect to a new stranger when the current stranger disconnects with  
`omeglebot: /popcorn`
  
Turns off popcorn  
`omeglebot: /unpopcorn`  
  
Connect to a stranger  
`omeglebot: /connect`

Disconnect from the current stranger  
`omeglebot: /disconnect`

Direct the stranger's responses to a specific user, this user will not need to mention omeglebot to send a message  
`omeglebot: /pipe username`

Unpipe with:  
`omeglebot: /unpipe`
 
If you need to enter a captcha use  
`omeglebot: /captcha`

Display the available commands  
`omeglebot: /help`
