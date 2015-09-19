# ephemeral-tweets
DESTROY YOUR TWEETS (if you're into that sorta thing)

This script will delete your latest tweet(s) at random time interval.

It will run in the background...until you kill it.

Install python-twitter API wrapper:

- pip install python-twitter

You'll also need to setup a twitter app at https://apps.twitter.com. The app requires read/write permissions. Copy the generated consumer and app tokens, you'll need them.

In the script:

- Provide the generated API tokens to the "api" variable
- Change the "handle" variable to your username.

usage: python ephemeral-tweets.py &
