
### Ćwiczenie: Baza danych MS SQL Server w Azure

#### Cel:
Celem tego ćwiczenia jest zaznajomienie się z podstawami usługi Azure SQL Database oraz praktyczne zastosowanie nabytych umiejętności poprzez stworzenie bazy danych, połączenie się z nią oraz wykonanie operacji na danych.

#### Wymagania:
- Aktywne konto Microsoft Azure.
- Zainstalowane SQL Server Management Studio (SSMS) i Azure Data Studio.
- Podstawowa znajomość C# i .NET lub innego języka programownia (do zadania programistycznego).

---

#### Krok 1: Utworzenie konta w Azure

1. Rejestracja na stronie [Azure](https://azure.com/).
2. Aktywowanie subskrypcji (możliwość skorzystania z darmowej subskrypcji dla nowych użytkowników).
3. Logowanie do [Azure Portal](https://portal.azure.com/).

---

#### Krok 2: Utworzenie instancji Azure SQL Database

##### a. Tworzenie zasobu
1. Na pulpicie nawigacyjnym portalu Azure wybierz „+ Utwórz zasób”.
2. Wpisz „SQL Database” w wyszukiwarce i wybierz.
3. Kliknij „Utwórz”.

##### b. Konfiguracja projektu
1. Wybierz lub utwórz grupę zasobów.
2. Wpisz nazwę dla bazy danych.

##### c. Wybór źródła danych
1. Wybierz opcję tworzenia nowej bazy, skorzystaj z przykładowej bazy danych lub skopiuj istniejącą.

##### d. Konfiguracja serwera
1. Utwórz nowy serwer lub wybierz istniejący.
2. Ustaw nazwę serwera, lokalizację, nazwę administratora i hasło.

##### e. Wybór opcji cenowych i rozmiaru
1. Wybierz plan cenowy i rozmiar.

##### f. Dodatkowe ustawienia
1. Skonfiguruj kopie zapasowe, replikację geograficzną i zabezpieczenia.

---

#### Krok 3: Zatwierdzenie i wdrożenie

1. Kliknij „Przejrzyj i utwórz” i sprawdź konfigurację.
2. Kliknij „Utwórz” aby rozpocząć tworzenie bazy danych.

---

#### Krok 4: Połączenie z bazą danych

1. Po utworzeniu bazy danych użyj SSMS i Azure Data Studio, aby się z nią połączyć.
2. W SSMS wpisz dane serwera, nazwę użytkownika i hasło.

---

#### Krok 5: Tworzenie aplikacji

1. Stwórz prosty program w technologii .NET lub innej, który połączy się z bazą danych.
2. Użyj Entity Framework lub innego ORM do pobrania i wyświetlenia danych.
3. Zaimplementuj funkcjonalność wyświetlania danych w konsoli lub interfejsie użytkownika.

---

#### Krok 6: Konfiguracja maszyny wirtualnej

1. Stwórz maszynę wirtualną w Azure.
2. Zainstaluj na niej SQL Server.
3. Skonfiguruj reguły sieciowe, otwórz porty.
4. Dostosuj ustawienia Windows Defender, aby umożliwić komunikację z bazą danych.

---

#### Krok 7: Praca z Azure Table Storage

##### Tworzenie tabeli:
1. W portalu Azure otwórz swój Storage Account.
2. Przejdź do sekcji "Table storage" i utwórz nową tabelę.

##### Dodawanie danych:
1. W portalu Azure użyj interfejsu graficznego do dodania danych do tabeli.

##### Pobieranie danych z C# lub inna technologia:
1. Użyj Azure Storage SDK w aplikacji .NET.
2. Skonfiguruj połączenie i zapytanie do Table Storage.
3. Pobierz dane i wyświetl je w aplikacji.
4. Obsłuż operacje CRUD 
---

### 1. Konfiguracja Firewalla Azure SQL Database

**a. Logowanie do Portalu Azure:**
   - Użyj swojego konta Microsoft, aby zalogować się na [portal.azure.com](https://portal.azure.com/).

**b. Przejście do Azure SQL Database:**
   - W panelu nawigacyjnym po lewej stronie znajdź i wybierz "SQL databases" (Bazy danych SQL).
   - Wybierz bazę danych, której zabezpieczenia chcesz skonfigurować.

**c. Konfiguracja zasad firewalla:**
   - W menu po lewej stronie wybierz opcję "Set server firewall" (Ustawienia firewalla serwera).
   - Kliknij na "+ Add client IP" (Dodaj IP klienta), aby dodać swój obecny adres IP, lub wpisz określone adresy IP, które mają mieć dostęp do bazy danych.
   - Możesz dodać zakres adresów IP w polach "Start IP" (Początkowy IP) i "End IP" (Końcowy IP).
   - Po zakończeniu kliknij "Save" (Zapisz).


## Azure Cosmos DB
Azure Cosmos DB jest globalnie rozproszoną bazą danych NoSQL oferującą szeroką skalowalność i elastyczność, przeznaczoną do aplikacji, które wymagają obsługi dużych ilości danych i globalnego dystrybuowania tych danych dla osiągnięcia niskiej latencji. Zapewnia ona wielomodelowe przechowywanie danych, które umożliwia wykorzystanie dokumentów, par klucz-wartość, grafów oraz kolumnowych rodzajów danych w jednej usłudze.
 
### Ćwiczenie: Wprowadzenie do Azure Cosmos DB

**Cel ćwiczenia:**
Poznanie podstaw Azure Cosmos DB poprzez stworzenie i interakcję z bazą danych dokumentowej. Celem jest stworzenie kontenera aby dodawać i pobierać dokumenty JSON oraz zarządzać skalowalnością.

**Zakres ćwiczenia:**

1. **Stworzenie konta Azure Cosmos DB:**
   - Utwórz nowe konto Azure Cosmos DB z wybranym API (np. SQL API, który jest interfejsem opartym na JSON i obsługuje język zapytań podobny do SQL).
   - Wybierz region, który jest najbliżej użytkownika, aby zoptymalizować wydajność.

2. **Tworzenie bazy danych i kontenera:**
   - Utwórz nową bazę danych w panelu zarządzania Cosmos DB.
   - Stwórz kontener (collection) z partycjonowaniem według wybranego klucza.

3. **Dodawanie i pobieranie danych:**
   - Wykorzystaj Data Explorer w Azure Portal do dodawania dokumentów JSON do kontenera.
   - Wykonaj zapytania za pomocą języka zapytań Cosmos DB, aby pobrać dodane dokumenty.

4. **Skalowanie i monitorowanie:**
   - Zbadaj możliwości skalowania poziomego w Cosmos DB i zmodyfikuj liczbę jednostek przetwarzania żądań (RU/s).
   - Wykorzystaj Azure Monitor, aby śledzić wykorzystanie i wydajność bazy danych.

5. **Integracja z aplikacją:**
   - Napisz prostą aplikację w C# (lub innym języku) używając Azure Cosmos DB SDK, która połączy się z Twoją bazą danych.
   - Implementacja CRUD (Create, Read, Update, Delete) operacji na danych.


### Sprawozdanie i ocena
 Celem jest wykonanie ćwiczeń i napisanie sprawozdania w formie instrukcji co krok, po kroku należało wykonać aby osiąnać cel. Sprawozdanie powinno być napisane w markdown i umieszczone na serverze np github. Sprawozdanie powinno zawierać, oprócz opisu wykonanych kroków zrzuty ekranu i stanowić kompletne podsumowanie wykonanego zadania. Ćwiczenie można wykonać z użyciem intrefjesu portalu AZURE lub CLI - bardzo mile widziane jest pokazanie obydwu metod.  Ocena 5 punktów. Termin 31.10.2023
