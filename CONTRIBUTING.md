# Zasady współpracy

Ten projekt zawiera stronę z przewodnikiem po stolicach Europy.  
Dokument opisuje zasady dodawania nowych stolic oraz wprowadzania zmian w repozytorium.

## Nazewnictwo branchy

- Nowe prace wykonujemy na osobnych gałęziach tworzonych z `main`.  
- Dla dodawania stolicy używamy schematu: `stolica-imie`, np. `kopenhaga-kamil`.  
- Jedna gałąź powinna odpowiadać jednemu zadaniu / zmianie.

## Nazewnictwo commitów

- Commit powinien jasno opisywać wprowadzoną zmianę.  
- Zalecany format: krótko, w czasie przeszłym, np.:  
  - `Dodano sekcję Kopenhaga`  
  - `Zaktualizowano opis stolicy`  
  - `Poprawiono link do obrazu`  
- Unikamy opisów typu `zmiany`, `poprawki`, `test`.

## Pull requesty

- Po zakończeniu pracy na gałęzi wysyłamy zmiany komendą `git push` i tworzymy pull request do gałęzi `main`.  
- Tytuł PR powinien wskazywać zakres zmian, np. `Dodano stolicę Kopenhaga – Kamil`.  
- W opisie PR krótko wypisujemy, co zostało dodane (sekcja HTML, obraz, opis tekstowy).

## Komunikacja i zgłaszanie problemów

- Uwagi i błędy zgłaszamy w komentarzach do pull requestów lub w zakładce **Issues**.  
- Osoba weryfikująca sprawdza zmiany, może poprosić o poprawki, a po akceptacji łączy gałąź z `main`.
