# Harmonogram projektu #
## Wielowątkowy serwer chatu ##
### 1. Okienka ###
* Okno chatu (15.03.2016)
* Okno rejestracji
* Okno logowania (15.03.2016)
* Okno historii
### 2. Zapis i odczyt plików ###
* Zapis historii rozmowy Odczyt historii rozmowy
* Zapis i odczyt konfiguracji klienta i serwera
* Zapis logów serwera
### 3. Współbieżność ###
* Wielowątkowość prosta (1 klient – 1 wątek), wątek nasłuchujący (8.03.2016)
* Ograniczenie masowej wielowątkowości przy wielu użytkownikach (nIO)
* Mechanizm wrzucania wiadomości do skrzynek użytkowników
* Mechanizm przechowywania rozmowy
### 4. Bazy danych ###
* Baza danych użytkowników (JDBC, CRUD)
* Logowanie i rejestracja (logika leżąca po stronie serwera) sprawdzanie listy zalogowanych użytkowników
* Przetwarzanie nowych konwersacji
### 5. Komunikacja sieciowa ###
* Klasa serwer: nasłuchiwanie i akceptowanie połączenia (1.03.2016)
* Klasa klient: obsługa zdarzeń (8.03.2016)
* Obsługa plików (z paskiem postępu)
* Odczytanie wiadomości, wysłanie odpowiedzi (po stronie serwera i klienta), zorganizowanie protokołu komunikacji (1.03.2016)
### 6. Zaproponowane przez studenta ###
* Pokoje rozmów
* GUI + logika na serwerze
* Wysyłanie prywatnych wiadomości
* Możliwość przesyłania plików przez sieć
* Historia rozmów