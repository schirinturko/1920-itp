# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

- Aufzählung 1
  - Aufzählung 2
    - Aufzählung 3
- - Aufzählung 4
- - - Aufzählung 5

## Herrausheben:
```
git remote add origin https://github.com/htl-leonding/my-project.git
git push -u origin master
```

```
echo "# delete-me-please" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/htl-leonding/my-project.git
git push -u origin master
```

Eine Zeile : `GIT`

---------------------
---------------------

1. Repo erstellen
2. git clone https://github.com/schirinturko/1920-itp.git
3. .md Datei erstellen
4. git add DATEINAME
5. git commit -m 'KOMMENTAR'
6. git push -u origin master (-u ... fürs nächste Mal kein origin master eingeben müssen)
7. git pull origin master -> local Repo updaten
8. git checkout -b BRANCHNAME -> neue Branch erstellen
9. git checkout master -> zurück in die Haupbranch
10. git branck -d BRANCHNAME -> Branch löschen
11. 