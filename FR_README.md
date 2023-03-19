# ![Protect Logo](https://i.imgur.com/5ovpCPg.png) Protect **Token Reset**
Ce repository va enregistrer tous les tokens envoyés par une message sur Discord ou alors ceux qui souhaitent ce faire réinitialiser. Cela sécurise votre TOKEN en le supprimant automatiquement

## Que c'est-il passée ?

1) Vous vous êtes fait voler votre token
2) J'ai trouvé ce token
3) Je l'ai ajouté à ce repository

## Mais pourquoi ?

Discord regarde les repository publiques contenant des tokens.
Si jamais un est trouvé (et qu'il est encore valide) il sera **supprimé automatiquement** et le propriétaire recevra un mail l'informant to inform de vol.

Sécuriser votre token contre les mauvaises utilisations est l'un de vos devoir en tant que créateur de bot Discord !
Dans les mains de quelqu'un de plus malveillant, ça peut entraîner le spam des serveurs et des utilisateurs, la fuite de données ou même l'exécution d'un shellcode arbitraire sur votre serveur.

## Que faire ?
Récupérez un nouveau token et faites attention à ne pas de nouveau le publier !
La prochaine fois, il pourrait ne pas être supprimé mais utilisé par celui qui le trouve.

## Comment est-ce que ça a pu ce passer ?
- Veuillez vérifier votre serveir pour d'éventuelles fuites !
- Si vous tirez votre code de bot automatiquement de GitHub, veuillez ne pas téléverser votre `config.json` et l'ajouter au gitignore !
- Si vous utilisez heroku/repl.it or glitch faites attention d'utiliser la manière spécifiée par la plate-forme de fournir des justificatifs d'identité (voir ci-dessous)
- Faites attention à qui vous donnez les informations sensible ou les commandes `eval`/`exec`.
- Faites toujours attention de retirer le token des debugs data que vous pourrez poster sur le net ou sur le salon d'un serveur support.

## Liens
Heroku: https://devcenter.heroku.com/articles/config-vars  
Repl.it: https://repl.it/site/docs/repls/secret-keys  
Glitch: https://glitch.happyfox.com/kb/article/18-how-do-i-store-secrets-credentials-or-private-data/  
GitIgnore: https://git-scm.com/docs/gitignore  
Informations sensibles on GitHub: https://help.github.com/en/articles/removing-sensitive-data-from-a-repository  

### Creation Serveurs
Discord: https://discord.gg/5C8Bg8CeMf
Website: https://protect-bot.fr
Email: https://discordapp.com/oauth2/authorize?client_id=614755681936867328&scope=bot%20applications.commands&permissions=8 
