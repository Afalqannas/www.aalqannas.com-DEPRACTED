# aalqannas.com
This is a django blog

#### Deployment notes:
environment variables path: /etc/config.json

and to load the environment variables from config.json add these lines in settings.py:

with open('/etc/config.json') as config_file:<br>
&nbsp;&nbsp;&nbsp;&nbsp;    config = json.load(config_file)

