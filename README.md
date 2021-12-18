# Informações úteis

## Comandos PHP
#### Versão PHP
pvp -v

## Comandos COMPOSER
#### Versão composer
composer --version
## Criando projeto laravel e estrutura lavarel
composer create-project laravel/laravel nome-do-projeto
#### Instalador de Laravel no PC
composer global require laravel/installer
#### Instalar pasta vendor
composer install

## Comandos LARAVEL
#### Criar projeto com o Instalador do Laravel
laravel new nome-do-projeto
(Se der erro pode ser que o composer não esta no PATH no sistema)

## GIT
#### Como este arquivo já foi versionado anteriormente é necessário limpar o cache local do repositório, para isso é necessário executar:
´´´
git rm -r --cached nome arquivo
´´´
####
git add .
####
git commit -m "gitignore funcionando"

## Outros
#### Baixar template themes forest
wget --mirror -p --convert-links -erobots=off URL
