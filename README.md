# CREDAX - FAST AI POWERED FUZZING TOOL with SLACK NOTIFICATIONS
Credax -Fastest Fuzzing Tool with Slack Notifications.

Credax is a lite-weight AI Powered Fuzzing Tool built in Python. Credax uses the least of you CPU by using more concurrent tasks thus saving your OS Threads, providing you with better speed and results. 

# INSTALLATION

Credax requires Python3.7 + to run. Please upgrade your Python version to 3.7 or higher to use Credax.

1 .Clone the Credax reporitory.

`git clone https://github.com/notmarshmllow/credax.git`

2 .Install the Requirements

`pip3 freeze > credax.py`

`python3 credax.py -h`

# EXAMPLE USAGE

Credax is lite-weight tool built for speed and effeciency. 
The following usage examples show the simplest task you can accomplish with `Credax`.
  
  
  ![alt text](https://github.com/notmarshmllow/credax/blob/main/credax.png?raw=True)
  
  
  Examples :
  
 # BASIC FUZZING
  
  `python3 credax.py -d https://example.com/ -w wordlist.txt`
  
  # SEND NOTIFICATIONS TO SLACK
  
  `python3 credax.py -d https://example.com/ -w wordlist.txt -s`
  
  # PRINT RESULTS TO A FILE
  
  `python3 credax.py -d https://example.com/ -w wordlist.txt -o filename.txt`
  
  
  # SLACK NOTIFICATIONS
  
1. Create your own Slack App.
2. Go to api.slack.com
3. Select your App
4. Select `Add features and functionality` > `Incoming Webhooks`.
5. Below on the page you will find your `Slack Webhook URL`.
6 .Copy and Paste you Slack Webhook URL in place of `_slack_webhook_url_here` inside `slack_variables.py` file
