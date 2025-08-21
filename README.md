# CyberGuru OSINT Workstation

<div align="center">

![CyberGuru OSINT Workstation](https://img.shields.io/badge/CyberGuru-OSINT%20Workstation-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Debian%2012%20%7C%2013-red?style=for-the-badge)

**Pierwsza polska stacja robocza OSINT - od zera do eksperta w 15 minut**

*Automatyczna instalacja i konfiguracja profesjonalnego środowiska OSINT używanego w kursie "Mistrzostwo w białym wywiadzie"*

</div>

---

## 🎯 O projekcie

Stworzyłem ten skrypt, ponieważ każdy analityk OSINT zna ten problem: **20+ godzin** spędzonych na ręcznej instalacji dziesiątek narzędzi, konfiguracji Firefox z odpowiednimi rozszerzeniami, ustawieniu prywatności i personalizacji środowiska pracy.

**Moje rozwiązanie** automatyzuje cały ten proces w **15 minut**.

Ten skrypt jest wykorzystywany w moim kursie **["Mistrzostwo w białym wywiadzie"](https://sklep.pawelhordynski.com/checkout/mistrzostwo-w-bialym-wywiadzie)** - jedynym polskim kursie OSINT na rynku, gdzie uczę praktycznych technik białego wywiadu od podstaw do zaawansowanych metod.

---

## ⚡ Instalacja

### Wymagania
- **Debian 12 lub 13** (testowane i potwierdzone)
- **4GB RAM** (zalecane 8GB)
- **10GB** wolnego miejsca
- **Połączenie internetowe**

### Jedna komenda - 15 minut
```bash
curl -O https://raw.githubusercontent.com/p4b1o/osint-template/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

**To wszystko!** Za 15 minut masz gotową profesjonalną stację roboczą OSINT.

---

## 🛠️ Co instaluje mój skrypt

### Narzędzia OSINT (15+)
- **Sherlock** - wyszukiwanie nazw użytkowników w serwisach społecznościowych
- **theHarvester** - zbieranie informacji o domenach i adresach email
- **Ghunt** - zaawansowana analiza kont Google
- **Subfinder** - enumeracja subdomen
- **H8mail** - sprawdzanie wycieków danych i haseł
- **Photon** - szybki web crawler zaprojektowany dla OSINT
- **Search-That-Hash** & **Name-That-Hash** - identyfikacja i analiza hashów
- **WhatsMyName-Python** - wyszukiwanie usernames w różnych platformach
- **HTTPTrack** - tworzenie kopii lustrzanych stron internetowych
- **Exiftool** - analiza metadanych plików

### Firefox z 12 rozszerzeniami OSINT
- **uBlock Origin** - blokowanie reklam i trackerów
- **Firefox Containers** - separacja danych między witrynami
- **Wappalyzer** - identyfikacja technologii używanych na stronach
- **Fireshot** - tworzenie zrzutów ekranu całych stron
- **User-Agent Switcher** - zmiana agenta przeglądarki
- **Exif Viewer** - analiza metadanych obrazów bezpośrednio w przeglądarce
- **OneTab** - zarządzanie zakładkami i oszczędzanie pamięci
- **DownThemAll** - pobieranie wszystkich zasobów ze strony
- **Bulk Media Downloader** - masowe pobieranie plików multimedialnych
- **Copy Selected Links** - kopiowanie wybranych linków
- **Image Search Options** - wyszukiwanie obrazów w różnych serwisach
- **Search By Image** - wyszukiwanie odwrotne obrazów

### Dodatkowe aplikacje
- **Tor Browser** - anonimowa przeglądarka
- **OnionShare** - bezpieczne udostępnianie plików
- **Visual Studio Code** - edytor kodu
- **Flameshot** - zaawansowane zrzuty ekranu
- **Obsidian** - notatki i mind mapping
- **Telegram Desktop** - komunikacja
- **Draw.io Desktop** - tworzenie diagramów

---

## 🔒 Bezpieczeństwo i prywatność

Mój skrypt automatycznie konfiguruje Firefox zgodnie z najlepszymi praktykami bezpieczeństwa:

✅ **Ścisła ochrona przed śledzeniem**  
✅ **Blokowanie fingerprintingu**  
✅ **Konfiguracja WebRTC przeciw wyciekom IP**  
✅ **Wyłączenie telemetrii Mozilla**  
✅ **Automatyczne usuwanie cookies po zamknięciu**  
✅ **Ograniczenie dostępu do sensorów i geolokalizacji**  

### Personalizacja systemu
- Dostosowany dock GNOME na dole ekranu
- Ciemny motyw terminala
- Wyłączenie automatycznego zawieszania systemu
- Personalizowane tło pulpitu
- Ulubione aplikacje w menu startowym

---

## 📚 Kurs "Mistrzostwo w białym wywiadzie"

Ten skrypt jest integralną częścią mojego kursu **["Mistrzostwo w białym wywiadzie"](https://sklep.pawelhordynski.com/checkout/mistrzostwo-w-bialym-wywiadzie)**, gdzie:

🎯 **Uczę praktycznych technik OSINT** od podstaw do zaawansowanych metod  
🛠️ **Pokazuję jak używać każdego z zainstalowanych narzędzi**  
🔍 **Prowadzę przez rzeczywiste case studies**  
🇵🇱 **Wszystko w języku polskim** z polskimi przykładami  

Kurs to **jedyne polskie szkolenie OSINT** na rynku, które łączy teorię z praktyką i daje konkretne umiejętności potrzebne w pracy analityka.

---

## 📊 Dlaczego moje rozwiązanie?

| Cecha | Moje rozwiązanie | Konkurencja |
|-------|------------------|-------------|
| **Język** | 🇵🇱 Polski | 🇬🇧 Angielski |
| **Czas instalacji** | ⚡ 15 minut | ⏱️ 30+ minut |
| **Konfiguracja Firefox** | ✅ 12 rozszerzeń | ✅ Podstawowa |
| **Ustawienia prywatności** | ✅ Zaawansowane | ✅ Podstawowe |
| **Wsparcie kursu** | ✅ Mistrzostwo w białym wywiadzie | ❌ Brak |
| **Testowane na** | ✅ Debian 12, 13 | ✅ Różne systemy |

---

## 🚀 Korzyści

### Oszczędność czasu
**20+ godzin** ręcznej konfiguracji → **15 minut** automatycznej instalacji

### Standardizacja
Identyczne, optymalne środowisko dla wszystkich analityków w zespole

### Bezpieczeństwo
Predefiniowane ustawienia prywatności zgodne z najlepszymi praktykami

### Kompletność
Nie tylko narzędzia, ale całe środowisko pracy gotowe od razu

---

## 📄 Licencja

Projekt udostępniam na licencji MIT - możesz go swobodnie używać, modyfikować i dystrybuować.

---

<div align="center">

**Stworzony przez Pawła Hordyńskiego dla polskiej społeczności OSINT**

[🎓 Kurs "Mistrzostwo w białym wywiadzie"](https://sklep.pawelhordynski.com/checkout/mistrzostwo-w-bialym-wywiadzie)

*Twoja droga do profesjonalnego OSINT zaczyna się tutaj.*

</div>

