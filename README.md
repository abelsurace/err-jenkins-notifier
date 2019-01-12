# JenkinsNotifier

JenkinsNitofier is an Errbot (<http://errbot.io>) plugin to provide Jenkins build notification over chat platform (<https://jenkins.io>) it also allows to enquire job status or start job builds on demand, it can be used with Slack and other chat platforms suppoted by Errbot. This one is inspired in <https://github.com/benvd/err-jenkins> and <https://github.com/membrive/err-jenkins>.


## Requirements

This plugin has been tested with Python 3 and requires Python Jenkins :

```
pip3 install python-jenkins
```


## Installation

From the bot:

```
!repos install https://github.com/abelsurace/err-jenkins-notifier
```

Then use `!help` to see the available commands and their explanation.


## Configuration

You have to add the following variables to your `config.py` file:

```
JENKINS_URL = ''
JENKINS_USERNAME = ''
JENKINS_TOKEN = ''
```

Restart the bot. You can do that with the command `!restart`.


## Tested with

* Python 3
* Errbot 4.3.5
* python-jenkins 0.4.13

