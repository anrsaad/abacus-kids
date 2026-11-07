# Abaque Magique / المعداد السحري
Application Android native (Kotlin + Jetpack Compose) — jeu éducatif de calcul avec abaque, Français + العربية (RTL), hors ligne.

## Build avec GitHub (بلا Android Studio)
1. ارفع محتوى هاد الملف (المجلد AbacusKids كامل، بما فيه `.github`) لـ repository جديد على GitHub.
2. Actions → "Build APK" كيتلانصا بوحدو مع كل push (ولا Run workflow).
3. من آخر run نزّل الـ artifact **AbacusKids-APKs** → فيه `app-debug.apk` و `app-release.apk`.

## Installation sur le téléphone
1. Copie l'APK sur le téléphone (WhatsApp / USB / Drive).
2. Ouvre-le → autorise "Installer des applis inconnues" si demandé → Installer.
(Android 8.0+ ; mode release signé avec `app/abacus-release.jks`.)

## Build local
Android Studio Koala+ : Open → Run, ou `gradle assembleDebug assembleRelease`.
