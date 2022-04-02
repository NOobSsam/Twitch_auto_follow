## Twitch Follow Bot
## About
This tool automates following a desired Twitch channel. To use this tool, Twitch oAuth tokens are required, and need to be pasted in the config/oauth_tokens.txt file. 
This tool demonstrates how Twitch follow-botting works and how the Twitch API can be abused. 

Follow-botting is when a channel is followed by a number of fake accounts. These accounts are usually controlled by a computer or script, such as this one. 
Artificial engagement and botting limit growth opportunities for legitimate broadcasters and it violates Twitch policies. This tool demonstrates how a follow-bot works
and should be used for EDUCATIONAL PURPOSES only.

## Preview
![Picture](https://github.com/NOobSsam/Twitch_auto_follow/blob/main/assets/C5BJDrhv.png)

## Setup
- Python must be installed

1. If you dont have python installed, download python 3.7.6
and make sure you click on the 'ADD TO PATH' option during
the installation.

2. Install requirements by typing ```pip install requests``` and  ```pip install colorama``` in cmd.

3.  Add Twitch oAuth tokens to ```config/oauth_tokens.txt```.

4.  Make sure you are in the same directory as the folder you downloaded it in.  Type
```python main.py``` in cmd to run

## Tutorial
To get oAuth tokens you can use the converter in the tool. Simply paste the Twitch accounts you want to convert to oAuth tokens in username:password format in ```config/convert.txt```. The output tokens can be found in ```output/oauth_tokens.txt```. Most of the time, this may not work because captcha may be required.

To get oAuth tokens manually, open Chrome dev tools (Ctrl + Shift +I ), head over to the Network tab, follow any twitch account, inspect the http post request (gql) , and check the Authorization header for the token. Copy the whole text after OAuth.

![get oauth](https://github.com/NOobSsam/Twitch_auto_follow/blob/main/assets/nfollow.gif)

## Legal
The software designed to perform website security testing.
The author is not responsible for any illegal use of these programs.
This is 100% educational, please do not misuse this tool.


