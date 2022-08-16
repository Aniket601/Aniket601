#### Graphql error in instalooter not been resolved yet!

# Fully Automated Youtube Channel BY ANIKET JADHAV

🄵🅄🄻🄻 🅈🄾🅄🅃🅄🄱🄴 🄲🄷🄰🄽🄽🄴🄻 🄰🅄🅃🄾🄼🄰🅃🄸🄾🄽 🅂🅄🄸🅃🄴
```



Code to run a fully automated youtube that can scrape content, edit a compilation, and upload to youtube daily.






# All Features😶‍🌫️

    1. Interactive  Auto/Manual mode
    2. Makes Compilation (Intro & Outro)
    3. Auto Title, Description & Tags 
    4. Auto TimeStamps & Credits (Username & Caption from Video)
    5. Edit description.txt when in manual mode
    6. Add Watermark to final Video

# Quick Start🐿️

    git clone https://github.com/sam5epi0l/BotTuber.git
    cd BotTuber
    # add instagram credentials in config.py
    # add YouTube API v3 credentials to googleAPI.json (check instructions)
    pip3 install -r requirements.txt
    python3 botTuber.py

# Usage📄

    python3 botTuber.py -i # interactive mode
    python3 botTuber.py -a # Full automation
    python3 botTuber.py -m # manual mode
    python3 botTuber.py -h # help menu

# Instructions✅

1. [Download](https://github.com/sam5epi0l/BotTuber.git) the Github Repository

2. Download and install [Python3](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/) if necessary.

3. Install libraries with `pip3 install -r requirements.txt` or `python3 -m pip install -r requirements.txt` .

4. Get setup and create a Project with the Youtube API: https://developers.google.com/youtube/v3/quickstart/python
Be sure to follow it carefully, as it won't work if you don't do this part right.
Download your OATH file and name it as "googleAPI.json" in your project folder.

6. Create an instagram account and follow accounts you want to scrape from

7. Open config.py in a text editor and fill in instagram credentials

- Note that you can edit variables inside botTuber.py in a text editor and things such as MAX_CLIP_LENGTH, Title, Description, Tags, etc..

8. In terminal/cmd, run `instalooter login` and `instaloader --login {YOUR_USERNAME}`. Follow the instructions to login.

9. Run `python3 botTuber.py` in your computer terminal (terminal or cmd). You have to sign in to your Youtube Account through the link the script will give you. It's going to ask you: "Please visit this URL to authorize this application:..." so you copy that link, paste it in your browser, and then sign into your Google account. Then paste the authentication code you get back into your terminal. It will then say "Starting Scraping" and sign into your instagram account.

10. Type "A" to run automated script or "M" to manually decide what to do at each step

11. Enjoy your fully automated youtube channel! :) Note that for uploading public videos, you have to complete an audit for the Youtube API. See the note in the [Google Documentation](https://developers.google.com/youtube/v3/docs/videos/insert). Without this, you can only post private videos, but they approve everyone. Have fun!

