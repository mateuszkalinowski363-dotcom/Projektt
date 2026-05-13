
# Katalog Branżowy

## Cel strony:
### Strona na której będzie można znaleźc sklepy dopasowane do potrzeb użytkownika np. Elektronika, Meble itp.

---
## 1. Logika Biznesowa
####  Model Kategoryzacji: Sklepy są pogrupowane w predefiniowane kategorie (np. Elektronika, Dom, Hobby). Jeden sklep przypisany jest do jednej kategorii głównej.

####  Dynamiczne Filtrowanie (Real-time): Po wybraniu kategorii przez użytkownika, aplikacja wysyła zapytanie do bazy danych z filtrem WHERE category = 'wybrana_nazwa'.

####  Zasada "No-Reload": Zmiana kategorii nie odświeża całej strony, a jedynie komponent z listą sklepów

#### Zarządzanie treścią: Dane o sklepach są odseparowane od kodu – edycja nazwy lub linku w bazie danych natychmiast aktualizuje stronę u wszystkich użytkowników.
---
## 2. Stos Technologiczny
## Frontend:

#### JS: Odpowiada za dynamiczny interfejs.

#### CSS: System klas do szybkiego budowania wyglądu (odpowiada za responsywność, czyli działanie na telefonach).

## Backend:
#### JSON

# 3. Kluczowe Funkcje
### Dynamiczny Pasek Kategorii: Główne menu (np. Elektronika, Moda, Sport), które po kliknięciu błyskawicznie filtruje listę sklepów bez odświeżania całej strony.
---
### Wyszukiwarka Live: Pole tekstowe pozwalające znaleźć konkretny sklep po nazwie (filtrowanie wyników w czasie rzeczywistym podczas pisania).
---
## Sortowanie wyników: Możliwość ułożenia sklepów według:

### Alfabetycznie (A-Z).
---
# Cele na przyszłość:
### - Dodanie lokalizacji sklepów po wybraniu konkretnej marki sklepu

### - System dodawania opinii o różnych branżach

### - Dodanie opcji faworyzacji branż aby się wyświetlały na początku listy
