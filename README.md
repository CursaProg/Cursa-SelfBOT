# Cursa SelfBOT
Une envie de Raid ? Vous avez trouver le bon SelfBOT.
Ce SelfBOT n'est pas encore complet, il est encore en cours de développement mais il est déjà bien préparé. Une première version est maintenant disponible et nous y ajouterons de nouvelles commandes / fonctionnalités au fil du temps.

# Petite information
Le code étant obfusqué, ce profil GitHub pourrait se faire supprimé étant donné que le but du site est de faire de l'open-source clair. Quand vous téléchargerez les fichiers du bot, il vous faudra éxecuter le fichier `launch.bat`, ce qui fera un unzip des fichiers du bot. C'est le seul fichier de code présent sur le repo et il n'est pas obfusqué. C'est peut-être grâce à celui-ci que j'éviterai le ban.

# Comment l'installer ?
Il est très simple de l'installer, il vous faudra télécharger le code du SelfBOT, vous rendre dans le dossier `Storage` et aller dans le fichier `config.json`.
Par la suite, il vous faudra y indiquer votre token. Voici le contenu du config.json

```
{
	"token": "// token ici //",
	"prefix": "!",
	"raidname": "Raid With Cursa-SelfBOT",
	"msgtospam": "UN RAID A ÉTÉ LANCÉ AVEC CURSA-SELFBOT ! @everyone",
	"icon": "https://media.discordapp.net/attachments/771863050520231966/772454207613698068/Logo_carre.png",
	"afk": "off",
	"afkreason": "",
	"nitroclaimer": "off",
	"richpresence": "off"
}
```
Les champs commençant par `//` doivent être changés. Les autres ne sont pas obligatoire mais vous pouvez les modifier pour un outil plus personnalisé.

# Comment mettre en place le RichPresence ?
Pour mettre le RichPresence en place, il vous faudra l'activer dans le fichier se trouvant dans `Storage/config.json` et changer le champs `richpresence` en :
```
"richpresence": "on"
```
Ensuite, il vous faudra vous rendre dans le fichier se trouvant dans `Storage/richpresence.json` et y changer les informations commençant par `//`. Le reste peut être changé pour avoir un RichPresence plus personnalisé.
Voici le contenu du fichier :
```
{
    "botID":"// l'id de l'application //",
    "titre":"Cursa SelfBOT",
    "description":"Cursa SelfBOT V1.0.0",
    "largeIcon":"// première icone //",
    "largeIconText":"En train de développer",
    "smallIcon":"// deuxième icone //",
    "smallIconText":"Coding ..",
    "partySize":1,
    "partyMax":1
}
```

# Liens Utiles & Credits
- Cet outil a été créé et développé par **CursaProg**.
- Rejoingez notre [Discord](https://discord.gg/G2ywfjxw9F, "Cursa Project").
