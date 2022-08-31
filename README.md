# Android Kronometre

Kotlin ile geliştirilmiş basit bir Android kronometre uygulamasıdır. Uygulama
başlatma, duraklatma, kaldığı yerden devam etme ve sıfırlama işlemlerini
destekler.

## Özellikler

- Android `Chronometer` bileşeniyle geçen süreyi gösterme
- Başlat, duraklat, devam ettir ve sıfırla kontrolleri
- View Binding tabanlı arayüz erişimi
- Açık ve koyu tema kaynakları
- Android 5.0 ve üzeri cihaz desteği (`minSdk 21`)

## Kullanılan Teknolojiler

- Kotlin 1.7
- Android SDK 32
- AndroidX ve Material Components
- Gradle

## Çalıştırma

Projeyi Android Studio ile açıp Gradle bağımlılıklarının yüklenmesini bekleyin.
Ardından bir emülatör veya Android cihaz seçerek uygulamayı çalıştırın.

Komut satırından debug APK oluşturmak için:

```bash
./gradlew assembleDebug
```

APK dosyası `app/build/outputs/apk/debug/` altında oluşur.

## Proje Yapısı

- `app/src/main/java/.../MainActivity.kt`: kronometre davranışı
- `app/src/main/res/layout/activity_main.xml`: kullanıcı arayüzü
- `app/src/main/res/drawable/`: kontrol ikonları ve görsel kaynaklar
