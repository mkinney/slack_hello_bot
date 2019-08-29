Simple slack bot using python

    virtualenv -p python3 venv
    source venv/bin/activate
    pip install slackclient
    pip freeze > requirements.txt

[Create app](https://api.slack.com/apps?new_app=1)

Need to create a bot user and get the OAuth tokens.

Copy the .env.sample to .env

Edit .env to reflect the token

    source .env

Test that the hellobot can post to the random channel

    ./hello_to_random.py




