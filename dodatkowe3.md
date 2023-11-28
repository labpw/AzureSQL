### Ćwiczenie: Aplikacja webowa ASP.NET w Azure z integracją Azure Functions i Key Vault

#### Cel:
Celem tego ćwiczenia jest rozwinięcie umiejętności pracy z Azure, przez stworzenie aplikacji webowej ASP.NET, która wykorzysta Azure Functions do przetwarzania danych pogodowych oraz Azure Key Vault do zarządzania tajemnicami aplikacji.

 

#### Krok 1: Utworzenie konta w Azure

- Zainstalowane środowisko programistyczne, np. Visual Studio z zainstalowanym Azure development workload.
---

#### Krok 2: Utworzenie i konfiguracja Azure App Service

##### a. Tworzenie zasobu
1. W portalu Azure wybierz „+ Utwórz zasób”.
2. Wyszukaj „Web App” i wybierz.
3. Kliknij „Utwórz”.

##### b. Konfiguracja projektu
1. Wybierz lub utwórz grupę zasobów.
2. Wpisz nazwę dla swojej aplikacji webowej.
3. Wybierz plan cenowy i konfigurację (np. Free, Shared, Basic, Standard, Premium).

##### c. Ustawienia publikacji
1. Wybierz metodę publikacji (Kod lub Kontener Docker).
2. Skonfiguruj środowisko wykonawcze (np. .NET Core).

##### d. Ustawienia monitorowania
1. Włącz Application Insights dla monitorowania aplikacji.

---

#### Krok 3: Integracja z Azure Functions

1. Zintegruj Azure Functions, które zostały wcześniej skonfigurowane do przetwarzania danych pogodowych, z aplikacją webową poprzez stworzenie odpowiednich endpointów REST API.

---

#### Krok 4: Utworzenie i konfiguracja Azure Key Vault

1. W portalu Azure utwórz zasób „Key Vault”.
2. Dodaj wymagane tajemnice, takie jak ciągi połączeń, klucze API itd.

---

#### Krok 5: Konfiguracja Azure App Service do używania Key Vault

1. Skonfiguruj Managed Identity dla Azure App Service.
2. Ustaw uprawnienia dla identyfikatora zarządzanego, aby umożliwić dostęp do Key Vault.

---

#### Krok 6: Rozwój aplikacji webowej ASP.NET

1. Stwórz aplikację webową ASP.NET w wybranym środowisku programistycznym.
2. Zintegruj aplikację z Azure Key Vault, aby bezpiecznie zarządzać sekretami.
3. Zaimplementuj wywołania do Azure Functions, aby wyświetlać przetworzone dane pogodowe.

---

#### Krok 7: Wdrożenie aplikacji webowej na Azure App Service

1. Skorzystaj z Visual Studio lub innego narzędzia, aby opublikować aplikację na Azure App Service.
2. Skonfiguruj środowisko produkcyjne, korzystając z Azure CLI lub portalu Azure.

---

#### Krok 8: Testowanie i monitorowanie

1. Przetestuj działanie aplikacji w środowisku produkcyjnym.
2. Skorzystaj z Application Insights, aby monitorować wydajność i wykrywać błędy.

---

#### Krok 9: Dokumentacja i sprawozdanie

1. Dokumentuj każdy etap tworzenia i wdrażania aplikacji.
2. Przygotuj sprawozdanie w formacie markdown, które zawiera szczegółowy opis wykonanych kroków, zrzuty ekranu i fragmenty kodu.
3. Umieść sprawozdanie na platformie GitHub.

---

- **Termin**: Do 22.12.2023 r.

---

#### Uwagi:

- Zachęca się do użycia zarówno interfejsu portalu Azure, jak i Azure CLI.
- Prezentacja obu metod w dokumentacji będzie dodatkowo punktowana.
- Sprawozdanie powinno być kompleksowym przewodnikiem, który umożliwi innym powtórzenie procesu.