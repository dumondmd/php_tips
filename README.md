# PHP Tips
## Curso PHP

Curso de PHP recursos avançados

# PHP TIPS #001

## Baixe o composer.phar
No site oficial

## Cria o composer.json

Crie **composer.json** e coloque 

```
{
	"name": "dumondmd/phptips001",
	"description": "Conhecendo o Composer e Configurando IDE | PHP Tips #001",
	"minimum-stability": "stable",
	"license": "MIT",
	"authors": [
		{
			"name": "dumondmd",
			"email": "dmd.dumon@gmail.com",
			"role": "Developer",
			"homepage": "https://github.com/dumondmd"
		}
	],
	"config": {
		"vendor-dir": "vendor"
	},
	"autoload": {
		"psr-4": {
			"Source\\": "source/"
		},
		"files": [
			"source/Config.php"
		]
	},
	"require": {
		"phpmailer/phpmailer": "6.0.*"
	}
}	
```

Após isto rodar o **composer install** ou rode o  **composer update**




