# Cel
- Automatyzacja rejestracji na testy
- Wspomaganie organizacji realizacji testów
- Uproszczenie procesu wydawania wyników
# Zakres
## Obejmuje
- Wspomaganie procesu zapisu na test
- Wspomaganie organizacji pracy związanej z wykonaniem testu
- Ewidencja przebiegu testu
- Ewidencja pracowników realizujących zadania związane z przeprowadzaniem testu
- Ewidencja danych klientów
- Wspomaganie procesu wydawania wyników
- Zarządzanie cennikiem usług
- Wymiana danych z systemem FK

# Kontekst
Aktualnie laboratorium nie stosuje systemu wspomagającego ewidencję i realizację testów. System nie obejmie spraw FK, umożliwi natomiast eksport danych do istniejącego systemu FK. System powinien też przesyłać dane o wyniku wraz z danymi klienta do Sanepidu. Nie będzie obsługiwał on: gospodarki magazynowej ewidencji środków trwałych ani spraw kadrowo-płacowych. 

# Wymagania
## Funkcjonalne
### Obsługa klienta
- Zapis na test powinien być możliwy za pośrednictwem internetu, bez kontaktu telefonicznego
- System powinien zapewniać możliwość ewidencji testów
- Powinna być możliwość ewidencjonowania danych klientów
- Po wprowadzeniu (danych klienta czy etykiety czy coś) powinna być możliwość wydrukowania wyniku
- Wydanie wyniku powinno być możliwe na podstawie kodu wydawanego klientowi przy pobieraniu próbki do testu
- Klient powinien być informowany o dostępności wyniku poprzez np. SMS po odznaczeniu zadania jako wykonane przez pracownika
### Organizacja pracy
- System powinien zapewniać możliwość podglądu zadań do wykonania dla zalogowanego pracownika pralni z możliwością wyboru zadania wykonywanego (możliwośc wydruku informacji o zadaniu)
- Po realizacji pracownik powinien mieć możliwość odznaczenia zadania jako wykonanego i wpisania wyniku.
- W systemie będzie możliwość zarządzania aktualnym cennikiem usług pralni
- System ma zapewnić możliwość eksportu danych do systemu FK

<!--[Linkacz](../DaneKlienta/clientDataBeforeTest.xml)-->