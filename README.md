# Wingman AI — pobierz aplikację

Wydanie **Preview 0.3.5** dla Windows i macOS.

| System | Pobierz |
| --- | --- |
| Windows x64 | [Instalator EXE](https://github.com/LetsautomateDev/wingman-ai-releases/releases/download/preview/Wingman-AI-Windows-x64.exe) |
| Mac z procesorem Apple Silicon (M1 i nowsze), macOS 14+ | [Instalator DMG ARM64](https://github.com/LetsautomateDev/wingman-ai-releases/releases/download/preview/Wingman-AI-Mac-arm64.dmg) |
| Mac z procesorem Intel, macOS 14+ | [Instalator DMG Intel](https://github.com/LetsautomateDev/wingman-ai-releases/releases/download/preview/Wingman-AI-Mac-intel.dmg) |

[Archiwum wydań](https://github.com/LetsautomateDev/wingman-ai-releases/releases) · [Sumy SHA-256](https://github.com/LetsautomateDev/wingman-ai-releases/releases/download/preview/SHA256SUMS.txt)

Powyższe linki zawsze prowadzą do aktualnego wydania Preview i można je umieścić na własnej stronie.

Wersja 0.3.5 jest na Macu podpisana certyfikatem Developer ID i notaryzowana przez Apple, więc otwiera się bez ostrzeżenia o szkodliwym oprogramowaniu. Panel jest widoczny także nad aplikacjami w trybie pełnoekranowym. Skróty Ctrl/Cmd+Shift ze strzałkami, przecinkiem i kropką działają tylko przy widocznym panelu, więc po jego ukryciu nie blokują zaznaczania tekstu w innych programach.

## Instalacja i aktualizacje

Na Windows uruchom pobrany plik EXE. Instalator nie ma jeszcze certyfikatu wydawcy, więc w oknie SmartScreen wybierz „Więcej informacji”, a następnie „Uruchom mimo to”.

Na Macu otwórz DMG i przenieś aplikację do Applications. Przy przejściu z wersji 0.3.4 lub starszej macOS jednorazowo poprosi ponownie o zgody na Mikrofon i Nagrywanie ekranu oraz o dostęp do pęku kluczy (wybierz „Zawsze pozwalaj”).

Od wersji 0.3.1 aplikacja sprawdza nowe wersje automatycznie, jeśli ta opcja jest włączona w ustawieniach. Można też sprawdzić je w **Ustawienia → Aktualizacje**. Instalacja wymaga potwierdzenia. Jeśli w 0.3.2 nie da się zamknąć otwartego edytora, zakończ aplikację przez jej menu, uruchom ponownie i przejdź do aktualizacji. Pakiety aktualizacji są weryfikowane podpisem Tauri.

## Status Preview

To wydanie testowe. Migracja licencji ze starej aplikacji jest jeszcze przed nami; do aktywacji potrzebna jest licencja z nowej bazy. Dotychczasowa baza pozostaje bez zmian.

Kompilacja dla obu architektur Maca nie zastępuje testów dźwięku, uprawnień i Keychain na fizycznym komputerze. Aktualizację Windows z zainstalowanej wersji 0.3.1 do 0.3.2 przez aplikację potwierdzono 19 października 2026. Test aktualizatora na Macu i końcowe porównanie interfejsu 1:1 pozostają do odbioru.

To repozytorium udostępnia instalatory i pliki aktualizacji. Kod aplikacji jest przechowywany prywatnie.
