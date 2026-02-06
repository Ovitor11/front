# Curso-Frontend

# GIT

## Conceitos de versionamento
- Histórico
- Controle de versão
- Quem alterou
- O quê alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versao 1 | Versão 2

# Instalação do git

https://git-scm.com/

-Windows: https://git-scm.com/download/win
- Linux (apt-get): sudo apt-get install git
- Mac (brew): brew install git

# Criar conta no Github

## Clonar o projeto

# Commits
Informação de alteração
- após testado todo seu código
- git add
- git commit -m "mensagem"
- git push (enviar alterações para o repositório)
## GitFlow
-fluxo do git

### Branchs
 São ramificações / versões paralelas

 - main / master
 - Develop
 - DOD Definition of Done: critérios de aceite
 - versionamento 0.1.10

 git checkout -b dev (cria uma branch)
 git checkout  master (mudar de branch)

 ### Merge
Mescla de branchs

git merge main

### Pull Requests
Mescla de branchs no repositório
Permite code review
O repositório resolve os conflitos automaticamente


### cconfigura o GitFlow
git flow init
git flow feature start {nome-da-feature}
