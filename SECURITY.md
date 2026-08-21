# FrameDoctor Güvenlik Politikası

## Desteklenen sürüm

Güvenlik düzeltmeleri FrameDoctor'un GitHub Releases bölümünde yayımlanan en güncel sürümü
için değerlendirilir. Eski bir sürüm kullanıyorsanız önce güncel resmî sürümle doğrulama yapın.

## Güvenlik açığı bildirme

Bir güvenlik açığının kötüye kullanılmasını sağlayabilecek ayrıntıları herkese açık Issues
alanında paylaşmayın. Deponun **Security** sekmesinde özel bildirim seçeneği görünüyorsa
**Report a vulnerability** üzerinden bildirin. Bu seçenek görünmüyorsa, teknik sömürü
ayrıntılarını eklemeden [genel bir güvenlik bildirimi](https://github.com/Engin622/FrameDoctor/issues/new/choose)
oluşturun; özel iletişim kanalı buradan belirlenir.

Bildirimde mümkünse şunlar bulunmalıdır:

- Etkilenen FrameDoctor sürümü ve Windows sürümü
- Sorunun etkisi ve yeniden üretmek için gereken genel koşullar
- Dosya hash'i ve dosyanın indirildiği adres
- Kişisel bilgi, parola, anahtar veya üçüncü kişilere ait veri içermeyen kanıt

Bildirim incelenene kadar açığı yayımlamamanız rica edilir. Alındı onayı veya düzeltme süresi
garanti edilmez; ancak doğrulanabilen bildirimler etki ve uygulanabilirliğe göre ele alınır.

## Dosya doğrulama

Kurulum paketini yalnızca bu deponun [Releases](https://github.com/Engin622/FrameDoctor/releases)
bölümünden indirin ve README'de yayımlanan SHA-256 değeriyle karşılaştırın. Hash eşleşmesi
dosyanın belirtilen sürümle aynı olduğunu gösterir; dijital yayıncı imzasının veya kusursuz
güvenliğin yerine geçmez.

## Kapsam dışı durumlar

- Değiştirilmiş, yeniden paketlenmiş veya resmî olmayan kaynaktan edinilmiş dosyalar
- Desteklenmeyen eski sürümler
- Yalnızca SmartScreen'deki “Bilinmeyen yayıncı” uyarısı
- FrameDoctor'un kontrolü dışındaki Windows, sürücü veya üçüncü taraf yazılım açıkları
