# curso-frontend

# GIT
## Conceitos de versionamento
- Histórico
- Controle de versão
- Quem alterou
- O quê alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua


Arquivo A | versão 1 | versão 2 
Arquivo B | versão 1 | versão 2

## Instalação do Git

## Criar a conta no Github

## Clonar o projeto 
git clone https://github.com/josefino-pedro-114a93269/curso-frontendnew.git

# Commits
Informação de alteração
- após testado todo seu código
- git add *
- git commit -m "mensagem"
- git push (enviar alterações para o repositório)
- git pull (puxar / trazer alterações do Github para sua máquina)


## GitFlow
Fluxo do Git

...
### Branchs
são ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicdo)
- develop
- DOD Definition of Done: critérios de aceites
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)


### Merge
Mescla de brachs
Você pode precisar resolver conflitos manualmente

git merge main

### Pull Requests
Mescla de branch no repositório
Permite code review
o repositório resolve os conflitos automaticamente 
