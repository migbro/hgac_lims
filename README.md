# hgac_lims
django site to serve seqConfig

# set up site:
1. create ```hgac_lims/secret_settings.py``` file, must contain:
  - ```SECRET_KEY = 'some string'```
2. create the mysql database and grant access to a user.
3. create ```hgac_lims/my.cnf``` file with db credentials used in step 2:
```cnf
[client]
database = hgac_lims
user = username
password = password
host = localhost
default-character-set = utf8
```

