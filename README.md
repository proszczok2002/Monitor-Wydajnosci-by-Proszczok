# Monitor Wydajności by Proszczok

Dodatek do czytnika ekranu NVDA dla Windows. Odczytuje informacje o CPU, RAM, dyskach, sieci, baterii, systemie oraz kartach AMD, NVIDIA i Intel. Wyniki podaje głosem, może je skopiować lub odczytywać okresowo. W Eksploratorze i na pulpicie skrót `NVDA+Ctrl+Alt+S` podaje rozmiar pliku lub folderu; dla dysku podaje zajęte i wolne miejsce.

## Przed instalacją / Before installation

Monitor Wydajności działa samodzielnie w NVDA. Przed instalacją wyłącz lub odinstaluj wszystkie inne dodatki NVDA do monitorowania sprzętu, takie jak Resource Monitor, AMD Monitor, NVIDIA Monitor i GPU Monitor. Tylko jeden taki dodatek powinien być aktywny, aby uniknąć konfliktów skrótów.

Performance Monitor works independently in NVDA. Before installing, disable or uninstall all other NVDA hardware monitoring add-ons, such as Resource Monitor, AMD Monitor, NVIDIA Monitor and GPU Monitor. Keep only one hardware monitoring add-on active to avoid shortcut conflicts.

## Pobierz / Download

<!-- GENERATED_RELEASE_START -->
**Aktualna wersja / Current version: 3.17**

- [Pobierz dodatek `.nvda-addon` z proszczok.pl / Download from proszczok.pl](https://proszczok.pl/nvdamonitor/MonitorWydajnosciByProszczok-3.17.nvda-addon)
- [Pobierz ten sam dodatek z GitHuba / Download the same add-on from GitHub](https://github.com/proszczok2002/Monitor-Wydajnosci-by-Proszczok/releases/download/v3.17/MonitorWydajnosciByProszczok-3.17.nvda-addon)
- [Strona dodatku i instrukcja / Add-on page and instructions](https://proszczok.pl/nvdamonitor/)
- SHA-256 instalatora / installer: `302dad6ee8af5aef764a1339349f713d1b63c97a32eb381e3ec78338725d329b` (135566 bajtów / bytes)

W sekcji Karty sieciowe można wybrać, które karty Ethernet i Wi-Fi mają trafiać do raportów. Domyślnie odczytywane są tylko aktywne karty fizyczne, z pominięciem kart wirtualnych. Wybór działa w obu skrótach sieciowych i pełnym raporcie systemu. Windows mierzy transfer tylko na wybranych kartach. Usprawniono odczyty Wi-Fi oraz ograniczono powtarzanie zapytań o telemetrię AMD i Intel.
<!-- GENERATED_RELEASE_END -->

Otwórz pobrany plik, potwierdź instalację w NVDA i uruchom NVDA ponownie. Wymagane są Windows i NVDA 2024.1 lub nowszy.

Open the downloaded file, confirm installation in NVDA, then restart NVDA. Requires Windows and NVDA 2024.1 or later.

## Zgłoszenia i kontakt / Issues and contact

- [Zgłoś problem lub pomysł na GitHubie / Report a problem or suggest a feature](https://github.com/proszczok2002/Monitor-Wydajnosci-by-Proszczok/issues/new/choose)
- W dodatku: `NVDA → Narzędzia → Monitor Wydajności by Proszczok — ustawienia → Pomoc i wsparcie → Kontakt / wyślij zgłoszenie`.
- [Strona autora / Author's website](https://proszczok.pl/)

Przy zgłoszeniu problemu napisz, co się stało, jak to odtworzyć, oraz podaj wersję NVDA i dodatku. Nie publikuj haseł, tokenów ani prywatnych logów.

When reporting a bug, describe what happened, how to reproduce it, and the NVDA and add-on versions. Do not post passwords, tokens or private logs.

## Aktualizacje / Updates

Automatyczny aktualizator pobiera informacje i instalator **wyłącznie z [proszczok.pl](https://proszczok.pl/nvdamonitor/)**. GitHub udostępnia dodatkową kopię tego samego instalatora do ręcznego pobrania oraz służy do informacji o wersjach i zgłoszeń.

The built-in updater obtains update information and downloads **only from [proszczok.pl](https://proszczok.pl/nvdamonitor/)**. GitHub provides an identical installer for manual download, release information and issues.

Drzewo tego repozytorium zawiera tylko opis, bez kodu dodatku. Instalator jest załącznikiem wydania GitHub. Sam publicznie dostępny plik `.nvda-addon` jest archiwum ZIP zawierającym pliki Pythona. Automatyczne archiwa „Source code” na GitHubie zawierają wyłącznie treść repozytorium, a nie instalator. Licencja dodatku: GNU GPL 2.0 lub nowsza; informacje o autorach są w paczce. [Polityka prywatności / Privacy policy](https://proszczok.pl/privacy.html).

The repository tree contains information only, with no add-on code. The installer is attached to the GitHub release. The downloadable `.nvda-addon` is a ZIP archive containing Python files. GitHub's automatic “Source code” archives contain only the repository content, not the installer. The add-on is licensed under GNU GPL 2.0 or later; author credits are included in the package.
