# reddtweet-bot
A similar service to IFTTT, if a reddit post appear tweet onto twitter account. In this case, a bot automated account will be used.

## libraries required
Install these through Python's Pip commands:
   * PRAW
        * Reddit API wrapper for Python
        * install via pip: `pip install praw`
   * Tweepy
        * Twitter API wrapper for Python
        * install via pip: `pip install tweepy`
   * Requests
        * Python HTTP library
        * install via pip: `pip install requests`
## access tokens and keys
Head over to https://dev.twitter.com/apps , register an app and change permission of your app to 'Read and Write'. Just copy paste the consumer keys & secret and generate a new access token from the fresh start and copy paste those as well.

Google now requires an API key to access its URL shortener tool. To get this access code you will have to register at this page for [URL-Shortener authorization](https://developers.google.com/url-shortener/v1/getting_started#OAuth2Authorizing).

Even if you use Google's link shortening tool, Twitter will still process your link though its t.co's shortener. Twitter does this for all links. ___Ultimately it is recommended to default to Twitter's url shortener by setting the google api key variable to "" (a blank string).___

## execution
This program can be executed as an interpreter by adding this on the top of the python program
``` #!/usr/bin/env python ```
Ultimately, it will only require the execution of this line ``` $ ./bot.py```

## License
This project is licensed by MIT
