# Egao – asystentka na pasku zadań Windows

To repozytorium zawiera **tylko stronę do pobrania** aplikacji Egao (GitHub Pages).

🌐 **Strona:** https://stabodecrabo-gif.github.io/egao/
⬇️ **Pobieranie:** [najnowsze wydanie](https://github.com/stabodecrabo-gif/egao/releases/latest)

Egao to polska asystentka głosowa dla Windows 10/11 (x64): stoi na pasku zadań, reaguje na „Hej Egao”, uruchamia programy i gry, otwiera strony i foldery, prowadzi kalendarz z alarmami. Rozpoznawanie mowy i głos działają lokalnie.

## Bezpieczne pobieranie
Pobieraj pliki wyłącznie z zakładki **Releases** tego repozytorium i sprawdź sumę SHA256 (plik `SHA256SUMS.txt` w wydaniu):

```powershell
Get-FileHash .\Egao-Instalator-1.1.0-x64.exe -Algorithm SHA256
```

Wynik musi być identyczny z wartością w `SHA256SUMS.txt`. Aplikacja nie jest podpisana płatnym certyfikatem, więc Windows SmartScreen może pokazać ostrzeżenie: „Więcej informacji” → „Uruchom mimo to”.
