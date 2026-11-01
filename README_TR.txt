VETTAKIP ANDROID APK PROJESI

Bu proje, son VetTakip HTML sürümünü Android WebView uygulamasına sarar. Bölümler, tedavi kayıtları, kayıt geçmişi, düzenleme ve günlük/haftalık/aylık rapor ekranı korunmuştur.

APK NASIL ALINIR?
1) Bu ZIP dosyasını GitHub'a yeni bir depo (repository) olarak yükleyin. ZIP'i açıp içindeki VetTakipAndroid klasörünün içeriğini deponun ana dizinine koyun. .github klasörünün de yüklendiğinden emin olun.
2) GitHub deposunda Actions sekmesine girin.
3) "VetTakip APK oluştur" iş akışını seçip Run workflow düğmesine basın (push sonrası otomatik de başlar).
4) İşlem tamamlanınca ilgili çalıştırmanın Artifacts bölümünden VetTakip-Android-APK dosyasını indirin.
5) İnen ZIP'i açın. İçindeki app-debug.apk dosyasını Android telefonda açıp yükleyin. Android bilinmeyen kaynaktan yükleme izni isteyebilir.

UYGULAMA NOTLARI
- İnternet bağlantısı gerektirmeden yerel HTML arayüzü açılır.
- Kayıtlar Android uygulamasının kendi WebView depolamasında tutulur.
- Uygulamadaki "Yedek indir" düğmesi Android'de JSON yedeğini İndirilenler klasörüne kaydeder.
- "Yedek yükle" dosya seçiciyi açar.
- Uygulamayı kaldırmak veya uygulama verilerini temizlemek yerel kayıtları silebilir. Düzenli yedek alın.
- Bu debug APK kişisel kullanım/test içindir; Play Store dağıtımı için ayrıca imzalı release yapılandırması gerekir.
