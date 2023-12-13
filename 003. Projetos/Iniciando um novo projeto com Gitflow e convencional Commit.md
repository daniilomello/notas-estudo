# Iniciando um novo projeto com Gitflow e convencional Commit

Inicie um projeto git na pasta que deseja adicionar ao github

```bash
commitizen init cz-conventional-changelog --save-dev --save-exact
```

Crie um branch main para o repositório ao invés de usar a padrão master

```bash
git flow init
```

Crie um novo repositório definindo se vai ser privado ou público

```bash
gh repo create project-template --private --source=. --remote=origin
```

Adicione os arquivos ao staged

```bash
git add .
```

Crie um .github e adicione os templates de issue e pull request

```bash
mkdir .github
```

Crie um README.md descrevendo o projeto

```bash
mkdir README.md
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

Lembre-se de atualizar as permissões da Branch

```md
- Proibir commits na main
- Apenas utilizar Pull Request
```

Iniciando uma feature

```bash
git flow feature start NomeDaFeature
```

Finalizando uma feature para abrir uma PR

```bash
git flow feature publish NomeDaFeature
```