# Focus Desktop — Windows

Minimalistyczna aplikacja do skupienia i codziennego wykonania.

## Funkcje
- Focus na dziś
- 3 najważniejsze zadania
- „Czego dziś nie robię”
- jedna rzecz dla siebie
- timer 25 / 50 / 90 minut
- pełnoekranowy tryb skupienia
- licznik zakończonych sesji
- 3–5 małych zwycięstw dnia
- ocena dnia 1–10
- krótkie podsumowanie dnia
- historia zamkniętych dni
- streak zamkniętych dni
- zapis lokalny na komputerze

## Budowanie EXE przez GitHub
Workflow jest już w `.github/workflows/build-windows.yml`.

Jeśli `.github` nie wgra się przez stronę GitHuba:
1. Add file -> Create new file
2. Nazwa: `.github/workflows/build-windows.yml`
3. Wklej zawartość `BUILD_WINDOWS_YAML.txt`
4. Commit changes
5. Actions -> Build Focus Windows EXE
6. Pobierz artifact `Focus-Windows-EXE`

Nie potrzeba żadnych sekretów ani klucza podpisu.
