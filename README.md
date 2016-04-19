# Yaml Web Editor

Edit your yaml files using html form. Depends on Pyaml, Flask, Paramiko and re.

# Features

- dont edit/show sensitive data on web
- download yaml using ssh

# Install

- git clone https://github.com/gsilos/YamlWebEditor.git
- easy_install pyaml flask paramiko
- Edit web.py and set your prefered port
- put the public ssh key file named key.pub for paramiko in the same folder where web.py is in.
- Run: ./web.py
- Point your browser to: http://localhost

# TODO

- authenticating against active directory using python ldap
- delivery edited yaml using url
- backup
- publish yaml back to the origin
- restart daemons
- create button support textarea for small blocks of yml
- open hidden fields to specific users from specific ips.
- save string fields using single quote

