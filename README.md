# gitleaks-hook

According to the documentation you can run Gitleaks as a pre-commit hook. 

Copy the example pre-commit.py script 
into your directory: 

$ curl -sO  https://github.com/gitleaks/gitleaks/blob/master/scripts/pre-commit.py

Go to you repo and run:

$ git config --local core.hooksPath path/to/gitleaks-hook-directory/ 

This command will create an entry in your local .git/config file.
Also you can enable and disable your gitleaks for repo if run:

$ git config --local gitleaks.enable true
$ git config --local gitleaks.enable false

