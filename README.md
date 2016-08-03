# Redmine Command Line Tool

# Requisites
- [php](https://php.net)
- [composer](https://getcomposer.org)

# Installing
```shell
composer require global jaschweder/redmine
```

# Usage
Include your ```~/.composer/vendor/bin``` folder to the system PATH
```shell
    export REDMINE_HOST=<your_redmine_host>
    export REDMINE_USERNAME=<your_redmine_username>
    export REDMINE_PASSWORD=<your_redmine_password>

    redmine                 #list all issues
    redmine --help          #print help message
    redmine show <issue_id> #show details of the issue
    redmine open <issue_id> #open the issue in your default browser
```

# TODO
 - create issues
 - change issues status
 - transfer issues to another user
 - create macros
 - more...

 created by Jonathan A. Schweder <jonathanschweder@gmail.com>
