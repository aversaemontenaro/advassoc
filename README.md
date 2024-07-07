# aversaemontenaro.com.br

## Para instalar novas credenciais do github em computadores novos
00. brew install --cask git-credential-manager
## Remover referncias de repositorios anteriores
01. rm -rf .git

## Comecar um commit novo em um repositorio criado [no exemplo é o advassoc]
1. git init
2. git add .
3. git commit -m "description commit"
4. git branch -M main
5. git remote add origin https://github.com/aversaemontenaro/advassoc.git
6. git push -u origin main

## Atualizaçao de commit
    * git add . 
    * git commit -m "added readme and link whatsapp" 
    * git branch -M main 
    * git push -u origin main   |   git push

## Comando forca o upload de todo o projeto novamente
    * git push --force origin main
