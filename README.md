AutoDeploy-from-github
====================
How To
----------
- Requirements : 
	- Python
	- A json file : AutoDeploy.conf.json

Features
------------
- Auto deploy from github repository using a HTTPS server

CONF SAMPLE
-------
> **JSON CONF EXEMPLE**

> {
>	"port": 8001, 
>	"repositories": 
>	[{
>		"url": "https://github.com/Alex-Werner/AutoDeploy-from-github", 
>		"path": "/var/www/demo.optimoc.fr/",
>		"deploy": "echo deploying"
>	}]
>}

Changelog
------------
V 0.1 - Basic code

