# Witam panów

## Zaakceptujcie dodanie jako kolaborator do repozytorium, jak kogos pominąłem, to pisać

## Jak ktoś nie ma GITa na komputerze
1. Instalujecie z tej strony: https://git-scm.com/
2. Jak się zainstaluje, to imię i mail trzeba ustalić (może być imię@numer_albumu.com albo cokolwiek)
   ```bash
   git config --global user.name "Your Full Name"
   git config --global user.email "your@email.com"
   ```

## Tu co macie zrobić jak już macie GIT

1. Stwórzcie folder, w którym będziecie pracować
   1. metoda : przez eksplorator plików
   2. metoda : 
   ```bash
   mkdir folder
   cd folder
   ```

2. Klonujecie repozytorium
```bash
git clone https://github.com/78332uafm/Serwis-online-
```

3. Tworzycie nowy branch ze swoim imieniem i nazwiskiem i checkout do tego brancha
```bash
git checkout -b IMIE-NAZWISKO
```

4. Dodajecie plik do folderu (najlepiej, żeby wszyscy dodali html, który robiliście na wcześniejszych labach, CSS utrudni mi robotę)

5. Dodajecie plik do gita i commit
```bash
git add index.html
git commit -m "Dodano index.html - Imie Nazwisko"
```

6. Push do GitHuba (bez tego nie dostanę niczego)
```bash
git push origin IMIE-NAZWISKO
```

A czy ja coś przyjmę, to zobaczymy 
