# Projekt za pomocą użycia Cypress - Testy automatyczne dla aplikacji GoIT

## Opis projektu

Ten projekt zawiera implementację testów automatycznych wykorzystujących wzorzec Page Object Pattern do testowania funkcjonalności logowania na stronie [https://www.edu.goit.global/account/login](https://www.edu.goit.global/account/login).

### Testy

#### Test 1

1. Test otwiera stronę logowania [https://www.edu.goit.global/account/login](https://www.edu.goit.global/account/login).
2. Wykorzystuje polecenie logowania, które znajduje pole email, wprowadza adres email **[user888@gmail.com](mailto:user888@gmail.com)**, wprowadza hasło **1234567890**, a następnie kliknięcie przycisku **Log in**.
3. Po zalogowaniu, test znajduje przycisk w prawym górnym rogu, otwiera menu strony, znajduje przycisk **Log out** i kliknięcie na niego.
4. Po wylogowaniu, test wraca do strony logowania.

#### Test 2

1. Test wyświetla stronę logowania [https://www.edu.goit.global/account/login](https://www.edu.goit.global/account/login).
2. Używa własnego polecenia logowania, które znajduje pole email, wprowadza adres email **testowyqa@qa.team**, wprowadza hasło **QA!automation-1**, a następnie kliknięcie przycisku **Log in**.
3. Po zalogowaniu, test znajduje przycisk w prawym górnym rogu, otwiera menu strony, znajduje przycisk **Log out** i kliknięcie na niego.
4. Po wylogowaniu, test wraca do strony logowania.

### Page Object Pattern

W projekcie wykorzystano wzorzec Page Object Pattern, który pozwala na lepsze zarządzanie elementami interfejsu użytkownika poprzez wydzielenie logiki interakcji z poszczególnymi stronami do oddzielnych plików. Każda strona posiada własny plik w katalogu `pages`, co ułatwia utrzymanie testów i zmniejsza powtarzalność kodu.

### Struktura plików

- `pages`
  - `Login.js`: Page Object dla strony logowania.
  - `HomePage.js`: Page Object dla strony głównej.

Dzięki zastosowaniu wzorca Page Object Pattern, kod testów jest czytelniejszy, łatwiejszy w utrzymaniu i bardziej elastyczny.

## Autor
Autor: Weronika Skarbek
Kontakt: w3r0n1k4sk4rb3k@gmail.com

