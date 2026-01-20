# 🚀 Komendy Git Piotrek wyslij mi tu zad plsssssss

Zbiór najważniejszych poleceń Git, pomocny przy codziennej pracy z repozytoriami.

## 🛠️ Konfiguracja i Inicjalizacja
Zanim zaczniesz pracę, skonfiguruj swoje dane użytkownika.

| Komenda | Opis |
| :--- | :--- |
| `git config --global user.name "majchrzakp2005"` | Ustawia nazwę użytkownika. |
| `git config --global user.email "majchrzakpiotr@outlook.com"` | Ustawia adres e-mail. |
| `git init` | Inicjalizuje nowe repozytorium Git w folderze. |
| `git --version` | Sprawdza zainstalowaną wersję Gita. |

---

## 📁 Zarządzanie Plikami i Statusem


* `ls -a` – Wyświetla wszystkie pliki w folderze (w tym ukryty folder `.git`).
* `touch plik.txt` – Szybkie tworzenie nowego pliku.
* `notepad.exe plik.txt` – Otwiera plik w Notatniku (Windows).
* `git status` – Sprawdza aktualny stan repozytorium.

---

## 💾 Zapisywanie Zmian
Aby zapisać postępy, najpierw dodaj pliki do poczekalni, a potem wykonaj commit.

* `git add plik.txt` – Dodaje konkretny plik do indeksu.
* `git add -A` – Dodaje wszystkie zmiany (nowe, zmodyfikowane i usunięte pliki).
* `git commit -m "opis zmiany"` – Tworzy punkt zapisu z komentarzem.

---

## 🌿 Praca na Gałęziach (Branches)


* `git branch` – Wyświetla listę dostępnych gałęzi.
* `git checkout -b "nowaGalaz"` – Tworzy nową gałąź i przełącza się na nią.
* `git checkout master` – Powrót do głównej gałęzi.
* `git merge innaGalaz` – Scala wybraną gałąź z obecną.

---

## 🌐 Repozytorium Zdalne (GitHub)
Połączenie lokalnego projektu z serwerem.

* `git remote add origin https://github.com/LOGIN-GITHUB/git-projekt01.git` – Łączy lokalne repozytorium ze zdalnym.
* `git push -u origin master` – Wypycha zmiany na serwer GitHub.

---
> **Uwaga:** Pamiętaj, aby przed `git push` zawsze sprawdzić status projektu za pomocą `git status`.
