# Curso Front-end
### EBAC

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
Arquivo B | Versão 1 | Versão 2

## Clonar o projeto

## Commits 
Informação de alteração 
- após testado todo seu código 
- git add *
- git commit -m 'mensagem'
- git push (enviar alterações para o reporsitório)
- git pull (puxar / trazer alterações do GitHub para sua máquina)

## Git Flow
Fluxo do git

### Branchs
São ramificações do código / versões paralelas

- main / master (vai para a produção, quando o projeto é publicado)
- develop 
- DOD (Definition of Done: critérios de aceite)
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)


### Merge
Mescla de branchs
Você pode precisar resolver conflitos manualmente

git merge main

### Pull Request
Mescla de branchs no repositório
Permite code review
O repositório resolve os conflitos automaticamente


### Configua o GitFlow
git flow init
git flow feature start {nome-da-feature}