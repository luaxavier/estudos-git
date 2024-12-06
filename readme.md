# Estudos Git

## O que é?

## Onde é utilizado?

## Principais comandos

#### Inicializando repositorio
```
git init
```

#### Verificando status dos arquivos
```
git status
```

#### Adicionando Arquivos ao stage
```
git add nome-do-arquivo.txt
git add nome-*
git add *-arquivo.txt               
git add .
```

#### Comparando as mudanças feitas no arquivo
```
git diff
```

#### Registrando e confirmando mudanças
```
git commit
git commit -m "sua-mensagem"
git commit -am "sua-mensagem"
git commit --amend -am "sua-mensagem"
```

#### Listando os remote 
```
git remote -v
```

#### Listando as branch 
```
git branch -v
```


#### Enviando as mudanças para o repositorio remoto
```
git push 
git push nome-remote nome-branch
git push origin main 
```