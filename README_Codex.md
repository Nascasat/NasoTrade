# NasoTrade — pacchetto per Codex

Repository di destinazione:
https://github.com/Nascasat/NasoTrade

Obiettivo immediato:
- costruire una app Android funzionante;
- generare un APK Debug tramite GitHub Actions;
- usare JDK 17 / Android SDK 35;
- NON collegare ancora Coinbase o inserire API key reali.

Il repository GitHub al momento contiene solo il README, quindi questo pacchetto fornisce una base Android pulita da importare/implementare.

## Build locale
Richiede JDK 17 e Gradle 8.7:
    gradle assembleDebug

APK:
    app/build/outputs/apk/debug/app-debug.apk
