# Git verziókezelés

## Helyi repo

- helyi repo inicializitása
    > git init
- felhasználónév és email ellenőrzés:
    > git config user.email
    > git cinfig user.name
- ellenőrzés:
    > git status
- előkészítjük a comit-ra (a verzió lérehozására)
    > git add .
- ellenőrzés:
    > git status
- commit:
  > git commit -m "first commit"
- a commitok listázása
    > git log 

## helyi repo összekapcsolása a távoli repoval
- távoli repo létrehozása
- a helyi repo összekapcsolása a távolival
    > git remote add origin ...\\token@githzb.com
- a legelső alkalommal a push:
    > git push -u origin master
- a továbbiakban a push:
    > git push
    