# Commands
## Terminal
```
ls
ls -a
cd
cd ..
mkdir
rm
mv archivo destino
```
Flujo de trabajo:
- Computador
- Stage
- Commit
- Server
## Git
To stage:
```
git status
git status -s
git add nombre del archivo nombre del archivo
git add .
git rm nombre del archivo
git mv archivo destino
git restore --staged nombre del archivo
git restore
git log
git log --oneline
```
To commit:
```
git commit -m "Mensaje"
git commit
```
## Branches
```
git branch
git checkout
git checkout -b nombre de rama
<<<<<<< HEAD
git merge
=======
>>>>>>> ramaB
```