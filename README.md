# Création Serveurs **Token Reset**
This repository will log all tokens send in a message on Discord. This is to secure your token by resetting it

## What happened

1) You leaked your token.
2) I found your token.
3) I uploaded it to this gist.

## But why?

Discord checks public repository for tokens.
If one is found (and it's still valid) it will be **invalidated automatically** and the owner will receive an email to inform them of the leak.

Securing your token against misuse is one of your duties as a Discord bot creator!
In the hands of someone more malicious it might cause servers and users to be spammed, data to be leaked or even arbitrary shellcode to be executed on your host server.

## What to do?
Get a new token and take care to not post it publicly again.
Next time it might not get invalidated but used by whoever finds it.

## How did this happen?
- Please check your application for possible leaks!
- If you pull your bot code automatically from GitHub please do not upload your `config.json` and add it to the gitignore!
- If you use heroku/repl.it or glitch please make sure to use the platform specified way of supplying credentials (see below)
- Please be careful who you give access to sensitive data or eval/exec commands.
- Always make sure you remove the token from debug data you might post on the net or in discord support channels.

## Links
Heroku: https://devcenter.heroku.com/articles/config-vars  
Repl.it: https://repl.it/site/docs/repls/secret-keys  
Glitch: https://glitch.com/help/env/  
GitIgnore: https://git-scm.com/docs/gitignore  
Sensitive Data on GitHub: https://help.github.com/en/articles/removing-sensitive-data-from-a-repository
