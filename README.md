# curso-de-git

## COMEÇANDO O NOVO CURSO DE GIT ![DOG](https://pipz.com/static/images/blog/eddie.png)

##Iniciando um Projeto Rapidamente

1 - Crie um novo repositório no Github

2 - Crie uma pasta vazia

3 - Crie um arquivo utilizando o seguinte comando: 
```bash
echo "# Meu Curso de Git" >> README.md
```
4 - Inicie o repositório:
```bash
git init
```

5 - Aceito as mudanças no arquivo README.md, utilizando:

```bash

git add README.md
```

6 - Faço o commit das mudanças utilizando:

```bash
git commit -m "Iniciando o projeto"
```
 
 7 - Crie a brench principal utilizando: 
 ```bash
 git branch -M main
 ```
 
 8 - Adicione a origem do repositório remoto (github):

 ```bash
 git remote add origin https://github.com/Riuk2252/novo-curso-de-git.git
 ```
 
 9 - Sincronizando branchs: 
 ```bash
 git push -u origin main
```
