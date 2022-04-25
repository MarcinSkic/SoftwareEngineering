# Historyjki klienta
## Przykładowe osoby
1. Klient
2. Kierownik
3. Właściciel
4. Klient, Pielęgniarka
5. Klient, Pracownik obsługi
6. Pracownik laboratorium

## Przykładowe historyjki
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

### Pobranie próbki
#### Jako
Pielęgniarka
#### Chcę
Zapisać dane na temat pobranej próbki
#### Aby
Test został zrealizowany

#### Zakładając, że
Wszystkie dane zostały podane
#### Jeżeli
Dane zostały wprowadzone do systemu, klient otrzymał kod odbioru wyniku i została naklejona etykieta na próbkę
#### To
Dane na temat próbki będą widoczne w systemie a zadania składające się na test zostaną w systemie zakolejkowane do wykonania.

### Przeprowadzenie testu
#### Jako
Pracownik laboratorium
#### Chcę
Zapisać wynik testu
#### Aby
Klient mógł go zobaczyć

#### Zakładając, że
Pracownik laboratorium zweryfikował wynik testu
#### Jeżeli
Wynik został wprowadzony do systemu
#### To
Test będzie widoczny w systemie jako wykonany a klient zostanie poinformowany o dostępności wyniku poprzez np. SMS

### Aktualizacja oferty
#### Jako
Kierownik
#### Chcę
Dodać dane na temat nowej placówki do przeprowadzania testów
#### Aby
Udostępnić informację o rozszerzonej ofercie klientom

#### Zakładając, że
Placówka jest gotowa rozpocząć pracę
#### Jeżeli
Podamy wszystkie informacje na temat placówki (nazwa placówki,adres, jakie testy są dostępne, w jakich godzinach jest czynna, dane kontaktowe)
#### To
Dane na temat placówki są dostępne w systemie i zostaje zaktualizowana dostępna oferta testów i terminów

### Udostępnienie wyników klientowi
#### Jako
Klient
#### Chcę
Otrzymać wynik testu
#### Aby
Poznać swój stan zdrowia

#### Zakładając że
Realizacja testu została zakończona i wynik jest gotowy
#### Jeżeli
Klient podał prawidłowy kod odbioru i dane osobowe (imię, nazwisko, PESEL)
#### To
Wynik zostanie wyświetlony klientowi z możliwością pobrania i wydrukowania