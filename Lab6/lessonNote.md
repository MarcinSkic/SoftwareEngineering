# Historyjki klienta
Patrzymy w sposób biznesowy, nie tylko funkcjonalności
Zagrożenie: skrajnie ogólne definiowanie historyjek lub zbyt szczegółowe lub zbyt techniczne (skierowane na konkretne funkcjonalności). Rozwiązanie: definiowanie kryteriów akceptacji, jak wskazać na daną funkcjonalność bez wchodzenie w zbyt duże szczegóły
Pierwszy wkład do tworzenia testów. Najważniejsze testy jednostkowe ale potrzebne są też End to end, integracyjne itd.
Skracają dystans od programisty do osoby biznesowej
## Sekcje
### Jako
Rola aktora biznesowego
### Chcę
Funkcjonalność jakiej chcemy użyć
### Aby
Konkretną korzyść, powód biznesowy
# Kryteria akceptacji
## Zakładając że

## To
Opisujemy efekt końcowy

# Testy jednostkowe
Integralna i niezależna część danego modułu, kodu. Mają się wykonywać jak najszybciej, mają pokrywać dużo kodu.
# Test integracyjny
Na żądanie, wykonywane z całą infrastrukturą (baza danych itp.)

# Historyjki z pralni
## Uczestnicy wydarzeń
1. Klient, Pracownik obsługi
2. Pracownik zaplecza
3. Właściciel
4. Kierownik, księgowy

## Przykładowe historyjki
### Przyjęcie zlecenia
#### Jako
Pracownik obsługi
### Chcę
Wprowadzić do systemu nowe zlecenie
### Aby
Zostało ono zrealizowane

### Kryteria akceptacji

#### Zakładając, że
Pracownik obsługi zweryfikował to zlecenie / Jesteśmy w stanie zrealizować to zlecenie
#### Jeżeli
Wprowadzimy do systemu dane zlecenia, rozliczyliśmy opłatę i został wydrukowany: paragon, potwierdzenie oraz etykiety do oznaczenia rzeczy 
#### To
Zlecenie będzie widoczne w systemie a zadania składające się na zlecenie zostaną w systemie zakolejkowane do wykonania.

### Wprowadzanie danych klienta do systemu
#### Jako
Pracownik obsługi klienta
### Chcę
Zaewidencjonować dane klienta w systemie
### Aby
Wprowadzić zlecenie na konkretnego klienta i móc wydać zlecenie bez potwierdzenia
### Zakładając, że
Klient zgodzi się na podanie swoich danych
### Jeżeli
Podamy wszystkie wymagane dane klienta (imię, nazwisko, numer telefonu, PESEL)
### To
Dane klienta są dostępne w systemie

# Diagramy kontekstowe
## Strukturalne:
Zorientowanie na dane
## Obiektowe:
Zorientowanie na funkcjonalność systemu

## Nasze historyjki
### Zarezerwowanie terminu przez klienta
#### Jako
Klient
#### Chcę
Wybrać termin i rodzaj testu
#### Aby
Posiadać rezerwację na test konkretnego dnia bez kontaktu telefonicznego

#### Zakładając że
Któryś wyświetlony termin odpowiada
#### Jeżeli
Klient poda wszystkie wymagane dane osobiste
#### To
Rezerwacja będzie widoczna w systemie i termin przestanie być dostępny dla innych klientów
