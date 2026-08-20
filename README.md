# FrameDoctor

![FrameDoctor](logo.png)

FrameDoctor, Windows 10 ve Windows 11 kullanan oyuncular için hazırlanmış yerel bir sistem sağlığı ve oyun performansı aracıdır. Karmaşık Windows ayarlarını tek arayüzde toplar; değişiklikleri kullanıcı onayıyla uygular ve geri alınabilir seçenekler sunar.

## Öne çıkan özellikler

- FPS, sistem yükü, GPU ve ağ değerlerini gösteren açılıp kapatılabilir ekran üstü gösterge
- Normal, Orta ve En İyi Performans profilleri
- Oyun algılandığında seçilen arka plan servislerini geçici olarak durdurma
- Başlangıç uygulamaları ve isteğe bağlı Windows uygulamaları yönetimi
- RAM, disk, ağ ve WinSAT tabanlı sistem kontrolleri
- Canlı bağlantı, dijital imza ve risk görünümü
- Riskli dosya oluşturma ve değiştirme olaylarını izleme
- Kontrollü Temp, shader önbelleği ve geri dönüşüm kutusu temizliği
- SFC, DISM, ağ sıfırlama ve geri yükleme noktası araçları
- Türkçe ve İngilizce arayüz
- Sistem tepsisi, Windows ile başlatma ve oyun oturumu özeti

## İndirme ve kurulum

En güncel paket: **FrameDoctor-Setup-v5.0.exe**

1. Kurulum dosyasını indirin.
2. Kurulum sihirbazını çalıştırın.
3. FrameDoctor sistem ayarlarını yönetebilmek için yönetici izni isteyecektir.
4. Uygulama içindeki seçenekleri kontrol ettikten sonra uygulayın.

> FrameDoctor şu anda ticari Authenticode sertifikasıyla imzalanmamıştır. SmartScreen ilk çalıştırmada bilinmeyen yayıncı uyarısı gösterebilir. Dosyanın SHA-256 değerini aşağıdaki değerle karşılaştırın.

## Dosya bütünlüğü

```text
CFAECCD445AA5FBCE5A04C2022BCAC2BE15BC60A99A5DE60D1B45085F3D5FA03  FrameDoctor-Setup-v5.0.exe
```

PowerShell ile doğrulama:

```powershell
Get-FileHash .\FrameDoctor-Setup-v5.0.exe -Algorithm SHA256
```

## Sistem gereksinimleri

- Windows 10 veya Windows 11
- 64-bit işlemci ve işletim sistemi
- Yönetici yetkisine sahip kullanıcı hesabı
- Bazı çevrim içi kontroller için internet bağlantısı

## Güvenlik ve gizlilik

- Reklam, telemetri veya kullanıcı hesabı içermez.
- Ağ görünümü hangi işlemin hangi adrese bağlandığını gösterir; şifreli trafiğin içeriğini çözmez.
- Sistem değişiklikleri kullanıcı seçimiyle uygulanır.
- Temizlik doğrulanmış Windows ve kullanıcı geçici klasörleriyle sınırlandırılmıştır.
- Windows güvenlik özelliklerini veya oyunların anti-cheat süreçlerini devre dışı bırakmayı amaçlamaz.

## Önemli not

Performans kazancı donanıma, Windows kurulumuna, sürücülere ve oyuna göre değişir. FrameDoctor belirli bir FPS artışı garanti etmez; amacı gereksiz arka plan yükünü azaltmak, sorunları görünür kılmak ve güvenli ayar yönetimi sağlamaktır.

## Geliştirici

FrameDoctor, Engin tarafından geliştirilmiştir.

Copyright © 2026 Engin. Tüm hakları saklıdır. Bu depo uygulamanın dağıtım kanalıdır; kaynak kod deposu değildir.
