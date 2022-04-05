# Cel
Celem systemu jest:
- automatyzacja ewidencji zleceń od klientów
- wspomaganie organizacji realizacji zleceń
- uproszczenie procesu wydawania zleceń
# Zakres
## Obejmuje
W zakres systemu wchodzi ewidencja zleceń, wspomaganie organizacji pracy związanej z realizacją zleceń, wspomaganie procesy wydawania zleceń
System powinien zapewnić opcjonalną ewidencję danych klientów, ewidencje pracowników którzy realizują zadania związane ze zleceniami oraz zarządzanie aktualnym cennikiem usług. W zakres systemu będą wchodziły czynności związane z wymiany danych z systemem FK oraz generowanie okresowych zestawień

Aktualnie w pralni nie jest stosowany system wspomagający ewidencji i realizacją zleceń

## Nie obejmuje:
Sprawami FK (finansowo-księgowe) ale umożliwi eksport danych do istniejące systemu FK
Nie będzie posiadał funkcjonalności obsługujących: gospodarką magazynową
ewidencją środków trwałych i spraw kadrowo-płacowych
W pierwszej wersji projektowany system nie będzie obsługiwał ewidencji i zarządzania reklamacjami

# Wymagania
## Funkcjonalne
### Obsługa klienta
- System powinien zapewniać możliwość ewidencji zleceń jedno zlecenie może składać się z wielu zleceń (jedno zamówienie usługi)
- Powinna być możliwość ewidencjonowania danych klientów, jednak podawanie danych nie będzie obowiązkowe, ma to na celu ułatwienie procesu wydawania zleceń
- Po wprowadzeniu zlecenia powinna być możliwość wydruku paragonu, potwierdzenia dla klienta oraz etykiet do oznaczenia pozostawionych rzeczy
- Wydawanie zleceń powinno być możliwe na podstawie potwierdzenia oraz identyfikacji klienta jeśli jego dane są w systemie
### Organizacja pracy
- System powinien zapewniać możliwość podglądu zadań do wykonania dla zalogowanego pracownika pralni z możliwośćią wyboru zadania wykonywanego (możliwość wydruku informacji o zadaniu)
- Po realizacji pracownik powinien mieć możliwość odznaczenia zadania jako wykonanego z możliwością ponownego wydrukowania etykiety do oznaczenia
- W systemie będzie możliwość zarządzania aktualnym cennikiem usług pralni
- System ma zapewnić możliwość eksportu danych do systemu FK
- W pierwszej wersji system powinien być dostępny raport wartośći zleceń za zadany okres
## Niefunkcjonalne
