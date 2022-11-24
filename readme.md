# Gitflow

Orientações para a utilização do github como versionamento de software.

`
Primeiramente, se faz necessária a criação repositório no github. 
Após isso, no computador, entrar no diretório em que deseja clonar o repositório.
O criador do repositório deve adicionar outros colaboradores ao projeto em Settings -> Collaborators.
Colaboradores devem aceitar se juntar ao projeto em Organizations -> Join -> Accept invite.
`

# DA UTILIZAÇÃO DO GIT

## Configurar usuario no seu git
```
git config --global user.email “email@email.com”
```

```
git config --global user.name “nome”
```

## Clonar repositório remoto existente para o local de trabalho
```
git clone https://github.com/drsavi/gitflow.git
```

## Exibir as condições (status) do diretório de trabalho e da área de staging
```
git status
```

## Adicionar alterações para o próximo commit
```
git add {nome do arquivo} {ou . pra incluir tudo}
```

## Adicionar alterações adicionadas na area de staging para o repositório
```
git commit -m "mensagem"
```

## Enviar o conteúdo do repositório local para um repositório remoto
```
git push
```
ou quando for o primeiro commit do repositório:

```
git push -u origin HEAD
```

## Exibir todas as branchs 
```
git branch -a
```

## Criar nova branc
```
git checkout -b {nome da nova branch}
```

## Mudar de branch
```
git checkout {nome da branch}
```

## Apagar branch local
```
git branch -D {nome da branch}
```

## Apagar branch remota
```
git push origin --delete {nome da branch}
```

## Arquivar alterações não commitadas do seu local de trabalho
```
git stash
```

## Aplicar as mudanças de um stash à área de trabalho 
```
git stash pop
```

## Unir duas branchs 
Ir para a branch que deseja aplicar as modificações
```
git merge {nome da outra branch}
```



