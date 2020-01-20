
# What's this?

It's a "simple" starter template for creating advanced discord bots using [discord.py](https://github.com/Rapptz/discord.py). There's a bit of a learning curve when it comes to using this template, unfortunately it's not documented cause I'm too lazy to write a documentation for it :>.

This template is basically [this template](https://github.com/SourSpoon/Discord.py-Template) but on steroids and much worse, so yeah good luck using it.

# Virtual Environment
What's a virtual environment you ask?

 A **virtual environment** is a tool that helps to keep dependencies required by different projects separate by creating isolated **python virtual environments** for them. This is one of the most important tools that most of the **Python** developers use.

It is recommended but not required to use a virtual environment to avoid any conflicts.
How do you setup a virtual environment you ask? Fear not I have a tutorial for that below.

# Installation
## Virtual Environment Installation
Open up your console or terminal and install the virtualenv package like so `pip install virtualenv`
**NOTE : This assumes that you have python3 installed**

## Cloning
Clone this repository like so `git clone https://github.com/Matt-cloud/Discord.py-Template.git`
This will create a folder named **Discord.py-Template** or smth like that.

## Creating a virtual environment
Simply write
```
virtualenv venv
```
You could rename venv to whatever you want. 

## Activating the venv
```
source venv/scripts/activate
```
or for windows
```
venv\scripts\activate
```
## Installing the required libraries
Please make sure you have already activated the venv.
```
pip install -r requirements.txt
```
After this you could finally start working on your precious discord bot.