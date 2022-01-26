# telebotbuilder

# <p align="center">telebotbuilder</p>

<p align="center">An aggregate of my frequently used packages when building a Telegram bot</p>

## Contents

  * [Getting started](#getting-started)
  * [Included Packages](#included-packages)
  * [Using telebotbuilder](#using-telebotbuilder)
  
      
## Getting Started

* Installation using pip (Python Package Index):

```
$ pip install telebotbuilder
```

## Included Packages

* pip install pyTelegrambotAPI
* pip install firebase
* pip install python_jwt
* pip install gcloud
* pip install sseclient
* pip install pycryptodome
* pip install requests-toolbelt

## Using telebotbuilder

You can just use the packages as normal. Here are some examples:

```python
# main.py

import telebot

bot = telebot.TeleBot(secrets.get_telebot_token())

bot.polling()
```

```python
# database.py

from firebase import Firebase

firebase = Firebase(secrets.get_firebase_config())
auth = firebase.auth()
db = firebase.database()
```

All's good, easier pip installs in the future!