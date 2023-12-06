## PŘÍKAZY:

Vypsat verzi gitu (dobré pro kontrolu): 
```
  git --version
```
Nastavit jméno  (jednorazove na zacatku):
 ```
  git config --global user.name "Jmeno Primeni"
```
Nastavit mail (jednorazove na zacatku):
```
  git config --global user.email jmenoprimeni@gmail.com
```
Zkontrolovat nastavené údaje (pro kontrolu):
```
  git config --list
```

Inicializovat prázný repositář:
```
  git init
```
Přidání všech změňených souborů do commitu:
```
  git add .
```
Vytvoření bodu v historii projektu - ucelený soubor změň:
```
  git commit -m "Naše commit message"
```
(Zobrazení historie commitů: git log)

Propojení Gitu s GitHubem: 
```
  git remote add origin https://github.com/vaseGitHubJmeno/vasNazevGitHubRepository.git
  git branch -M main
  git push -u origin main
```
Přidání změn z Gitu na GitHub:
```
  git push
```

Klonování vzdáleného repozitáře ke mně (půjdu do složky kam chci naklonovat):
```
  git clone https://github.com/GitHubJmeno/nazevRepositoryKteryKlonujeme.git
```
Pokud na konci terminalu napsáno (END) a nelze psát vyskočíme pomocí klávesy q

---

## TERMÍNY:
**Repositář/repository** = úložiště jednoho projektu

**Commit** = vytvoření bodu v historii projektu - ucelený soubor změň (**commit message** = popis našich změn)

---
## SITUACE:
Když pracuji s Gitem poprvé:
```
  git config --global user.name "Jmeno Primeni"
  git config --global user.email jmenoprimeni@gmail.com
```

Když vytvořím nový projekt (jednorázově na začátku projektu):

  A) Vytvořím Git repository:
  ```
    git init
  ```
  B) Propojím s GitHub repository:
  ```
    git remote add origin https://github.com/vaseGitHubJmeno/vasNazevGitHubRepository.git
    git branch -M main
    git push -u origin main
  ```

Když chci přidat změny (pravidelně s přidáváním změn):

  A) na Git:
  ```
    git add .
    git commit -m "Popis zmen"
  ```
  B) pak i na GitHub:
  ```
    git push
  ```
