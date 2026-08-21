# FrameDoctor Gizlilik Politikası

Son güncelleme: 21 Ağustos 2026
Geçerli sürüm: FrameDoctor 5.0

Bu politika, FrameDoctor masaüstü uygulamasının hangi verileri işlediğini ve bu verilerin
nerede tutulduğunu açıklar.

## Kısa özet

FrameDoctor kullanıcı hesabı, reklam veya ürün telemetrisi içermez. Uygulama; sistem,
performans, çalışan süreç, ağ bağlantısı ve dosya etkinliği bilgilerini görevini yerine
getirmek amacıyla yerel bilgisayarda işler. Bu bilgiler FrameDoctor tarafından merkezi bir
sunucuya gönderilmez.

## Yerel olarak işlenen bilgiler

Uygulama aşağıdaki bilgileri Windows API'leri üzerinden okuyabilir:

- İşlemci, RAM, ekran kartı, anakart, Windows sürümü ve disk bilgileri
- Anlık CPU, RAM, GPU, VRAM, FPS ve ping değerleri
- Çalışan süreçlerin adı, işlem kimliği ve erişilebildiğinde dosya yolu
- Aktif ağ bağlantılarının yerel/uzak IP ve port bilgileri
- Başlangıç kayıtları, ilgili Windows ayarları ve isteğe bağlı uygulama paketleri
- Dosya izleme kullanıcı tarafından açıldığında seçili dosya sistemi olayları
- Oyun oturumlarının süresi ve performans özeti

## Yerel saklama

Tercihler Windows kullanıcı kayıt defterindeki `SOFTWARE\FrameDoctor` alanında saklanabilir.
Oyun oturumu özetleri `C:\ProgramData\FrameDoctor` altında yerel olarak tutulabilir.
Kullanıcının oluşturduğu sistem raporu yalnızca seçilen yerel konuma kaydedilir.

Bu veriler kullanıcı tarafından Windows araçları veya FrameDoctor'un ilgili temizleme/kaldırma
işlemleri kullanılarak silinebilir.

## Ağ kullanımı

FrameDoctor aşağıdaki kullanıcı tarafından görülebilen ağ işlemlerini gerçekleştirebilir:

- Ping testi için belirtilen genel hedeflere ICMP isteği
- IP adreslerini alan adına çevirmek için Windows DNS çözümlemesi
- Kullanıcı VirusTotal seçeneğini seçerse ilgili arama sayfasını varsayılan tarayıcıda açma

FrameDoctor şifreli HTTPS/TLS trafiğinin içeriğini çözmez, paket içeriğini merkezi bir sisteme
yüklemez ve tarayıcı geçmişini okumaz. VirusTotal sayfasının kullanımı VirusTotal'ın kendi
gizlilik koşullarına tabidir; FrameDoctor seçilen dosyayı otomatik olarak VirusTotal'a yüklemez.

## Temizlik ve dosya inceleme

Temizlik özelliği kullanıcı onayıyla çalışır. Dosya inceleme özelliği seçilen dosyanın sınırlı
bir bölümünü yerel olarak okuyabilir. Okunan içerik FrameDoctor tarafından dışarı gönderilmez.

## Üçüncü taraflar

Windows, GitHub, VirusTotal, DNS sağlayıcıları ve oyun platformları FrameDoctor'dan bağımsızdır
ve kendi koşullarına tabidir. FrameDoctor bu hizmetlerin veri işleme uygulamalarını kontrol etmez.

## Çocukların gizliliği

FrameDoctor özellikle çocuklara yönelik bir çevrim içi hizmet değildir ve kullanıcı hesabı
oluşturmaz. Reşit olmayan kullanıcıların sistem ayarlarını bir ebeveyn veya sorumlu yetişkin
gözetiminde değiştirmesi önerilir.

## Değişiklikler

Bu politika uygulamanın davranışı değiştiğinde güncellenebilir. Güncel metin bu depoda ve ilgili
GitHub Release bilgilerinde yayımlanır.

## İletişim

Gizlilikle ilgili genel sorular GitHub Issues üzerinden, hassas güvenlik ayrıntıları ise deponun
Security bölümündeki uygun özel bildirim kanalı üzerinden iletilmelidir.
