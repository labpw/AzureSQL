### Ćwiczenie: Tworzenie i Wdrażanie Modelu ML do Rozpoznawania Obrazów z Azure Machine Learning i Integracja z Aplikacją C# MAUI

#### Cel:
Zapoznanie się z możliwością tworzenia, szkolenia, wdrażania modeli ML do rozpoznawania obrazów z Azure Machine Learning Studio i integracji z aplikacją mobilną C# MAUI.

#### Kroki:


1. i 2. **Przygotowanie Danych:**
   - Zaloguj się do Azure Machine Learning Studio.
   - W "Datasets" wybierz "Create dataset". Użyj zbioru danych obrazowych, np. CIFAR-10.

3. **Tworzenie Modelu ML:**
   - W zakładce "Designer" utwórz nowy eksperyment.
   - Użyj modułów do przetwarzania obrazów i wybierz sieć neuronową (np. CNN).

4. **Szkolenie Modelu:**
   - Uruchom eksperyment i monitoruj postępy.
   - Po zakończeniu sprawdź wyniki, np. dokładność klasyfikacji.

5. **Wdrażanie Modelu:**
   - Wybierz model i użyj "Deploy" do utworzenia endpointu.
   - Wybierz wdrożenie jako usługa sieciowa (web service).

6. **Tworzenie Aplikacji C# MAUI:**
   - Zainstaluj Visual Studio z obsługą MAUI.
   - Utwórz nowy projekt aplikacji MAUI.
   - Dodaj obsługę kamery i możliwość przesyłania zdjęć do endpointu Azure ML.
   - Skonfiguruj aplikację, aby korzystała z adresu URL i klucza API endpointu ML.

7. **Integracja Modelu z Aplikacją:**
   - Dodaj funkcję, która wywołuje endpoint ML i przekazuje mu zdjęcie.
   - Przetwórz odpowiedź od ML i wyświetl wynik na ekranie aplikacji.

8. **Testowanie Aplikacji:**
   - Przetestuj aplikację na różnych obrazach.
   - Zweryfikuj, czy aplikacja poprawnie identyfikuje obiekty na zdjęciach.

9. **Dokumentacja i Sprawozdanie:**
   - Dokumentuj każdy krok tworzenia modelu i aplikacji, włącznie z kodem i zrzutami ekranu.
   - Przygotuj sprawozdanie w markdown i umieść na GitHub.

#### Wymagania Dodatkowe:
- Zwróć uwagę na jakość i różnorodność danych treningowych.
- Upewnij się, że model jest odpowiednio dostrojony do zadania.
- Dokładnie opisz proces integracji modelu ML z aplikacją MAUI.

### Sprawozdanie i ocena
 Celem jest wykonanie ćwiczeń i napisanie sprawozdania w formie instrukcji co krok, po kroku należało wykonać aby osiąnać cel. Sprawozdanie powinno być napisane w markdown i umieszczone na serverze np github. Sprawozdanie powinno zawierać, oprócz opisu wykonanych kroków zrzuty ekranu i stanowić kompletne podsumowanie wykonanego zadania. Ćwiczenie można wykonać z użyciem intrefjesu portalu AZURE lub CLI - bardzo mile widziane jest pokazanie obydwu metod.  Ocena 15 punktów. Termin 12.01.2024