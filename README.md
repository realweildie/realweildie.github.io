# Homepager
Build your own homepage in minutes!
<img src="https://imgur.com/PpRuEZy.jpg">

## Why?!
Sometimes we don't have time to do something important. For example create your own homepage. <b>Homepager</b> solves this problem

## Creation:
1. Create Github repository with name <b>```username```.github.io</b> (where ```username``` is your Github username).
2. Clone it.
3. Clone ```https://github.com/jieggii/homepager.git```
4. Copy all files from <b>```homepager/```</b> into <b>```username.github.io/```</b>
5. Open <b>config.cfg</b> via any text editor
6. Set parameters as you need
7. Commit & push
8. Done! Locate to <b>https://```username```.github.io</b>

## Setting your own homepage:
### Example config:
```json
{  
  "github-username": "username",  
  "description": "Web developer",  
  "status": "Doing really cool stuff",  
  "social-media": [  
	  {"fa_icon": "fab fa-github", "url": "https://github.com/username", "color": ""},  
	  {"fa_icon": "fab fa-twitter", "url": "https://twitter.com/username", "color": "blue"},  
	  {"fa_icon": "far fa-envelope", "url": "mailto:email@example.com", "color": ""},  
	  {"fa_icon": "fab fa-instagram", "url": "https://instagram.com/username", "color": ""}  
  ]
}
```
* ```username``` - Your github username. If you change your it on github, you also should change it in ```config.json```
* ```description``` - Self-introducing. Tell who you are. For example "Web designer", "Web designer" or something like that
* ```status``` - Your status. For example "Learning", "Working", "Having fun" etc.
* ```social-media``` - List consisting of links to your social networks accounts
* * ```fa_icon``` - Icon classes from <a href="https://fontawesome.com/">Font awesome</a>. For example "<b>fab fa-github"</b> for github icon. Just search them <a href="https://fontawesome.com/icons?d=gallery">here</a>, then copy & paste classes into ```fa_icon``` value
* * ```url``` - Link to your social network account. <b>Must contain ```https://```</b>
* * ```color``` - Optional variable. Can be empty. Color of icon.

## License
<b>MIT</b>