voltar: [[Home]]
tópicos: [[004. MOC/Git]]
referências:
tags: #projeto 

# Criando um novo projeto no github pela cli

Inicie um projeto git na pasta que deseja adicionar ao github
```bash
git init
```
Crie um branch main para o repositório ao invés de usar a padrão master
```bash
git checkout -b main
```
Crie um novo repositório definindo se vai ser privado ou público
```bash
gh repo create notas-estudo --public --source=. --remote=origin
```
Adicione os arquivos ao staged
```bash
git add .
```
Realize o commit dos arquivos
```bash
git commit -m "feat: add initial react files"
```
Realize o push do projeto para a branch main
```bash
git push -u origin main
```
Abra o repositório no navegador para conferir
```bash
gh browse
```