# MyFixIt

## Setup
1. `pip install virtualenv`
    + [this is supposed to be useful](http://python-guide-pt-br.readthedocs.io/en/latest/dev/virtualenvs/ "Info")
2. In the clone of the repository make a virtual environment `virtualenv venv`
3. Activate the virtual environment: `\. venv\bin\activate` deactivate the virtual environment `deactivate` in Windows it will be in `venv\Scripts\activate`
4. Install the requirements `pip install -r requirements.txt` with the virtual environment activated
5. Use Allie's version of PyFixIt
    + [Clone or fork here](https://github.com/agiddings/pyfixit)
    + `pip install .` from root directory

## Setting up Alexa Skill in the Developer Console
1. Interaction Model:
    + current intent schema is in intent\_schema.txt
    + current sample_utterances is in sample\_utterances.txt
2. Configuration
    + Service Endpoint Type: https
    + region: NA
    + service endpoint link: <https://8qa3sct347.execute-api.us-east-1.amazonaws.com/dev>
3. SSL Certificate
    + My development endpoint is a sub-domain of a domain that has a wildcard certificate from a certificate authority

## Notes
I made the lambda using this [zappa tutorial.](https://developer.amazon.com/blogs/post/8e8ad73a-99e9-4c0f-a7b3-60f92287b0bf/new-alexa-tutorial-deploy-flask-ask-skills-to-aws-lambda-with-zappa "zappa tutorial")
If you don't feel like going through all that, feel free to use this as your service endpoint: <https://8qa3sct347.execute-api.us-east-1.amazonaws.com/dev>. It is the one I made.

Cole's end point: https://dhfu6hfvyj.execute-api.us-east-1.amazonaws.com/dev

[PyFixIt Wiki:](https://pyfixit.readthedocs.io/en/latest/ "PyFixIt")

# Adding the database
