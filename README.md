# Guía rapida Git

Este repo pretende ser una referencia para consultar de formaa rapida los comandos básicos de Git.



## Iniciar repo

``` bash
mkdir carpeta-proyecto
cd carpeta-proyecto
echo "# nombre-proyecto" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/user/nombre-del-repo.git
git push -u origin master
```

