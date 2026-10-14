# POKERVIX Poker – Gizlilik Politikası Paketi

Güncelleme tarihi: 14 Ekim 2026
Geliştirici: Victorium Soft
Uygulama paket adı: com.victoriumsoft.pokervix
Gizlilik iletişim adresi: victoriumsoft@gmail.com

## DOSYA SEÇİMİ — ÖNEMLİ

1) `site/` = ÇEVRİMDIŞI / REKLAMSIZ sürüm. Kullanıcı hesabı, çevrimiçi maç,
   reklam ve analiz SDK'sı olmayan sürüm için hazırlanmıştır.
2) `reklamli_surumu/` = Google AdMob REKLAMLI sürüm. Hesap, çevrimiçi maç,
   Play Games oturumu ve başka analiz SDK'sı olmayan sürüm için hazırlanmıştır.

Bunlar farklı olası uygulama yapılandırmalarına göre hazırlanmış TASLAKLARDIR.
Oyunun kaynak kodu/AndroidManifest.xml/SDK listesi verilmediği için hangi
sürümün gerçek uygulamayla uyumlu olduğu DOĞRULANMADI. Uygulamaya uymayan
metni yayımlamak Google Play reddine ve yanlış bilgilendirmeye neden olabilir.

## NASIL YAYIMLANIR?

1. Gerçekte kullandığınız SDK'ları, izinleri ve ağ bağlantılarını kontrol edin.
2. Yukarıdaki iki klasörden yalnızca gerçek davranışla uyumlu olanı seçin.
3. Seçtiğiniz klasörün içindeki index.html ve en/ klasörünü, herkese açık
   HTTPS web sitenize yükleyin.
4. Örnek konum: mevcut VictoriumSoft sitenizde
   `pokervix/privacy-policy/index.html` ve `pokervix/privacy-policy/en/index.html`.
   Böyle yüklerseniz örnek adres:
   https://www.victoriumsoft.site/pokervix/privacy-policy/
   (Bu adres paket yüklenene kadar mevcut/çalışıyor varsayılmamalıdır.)
5. Telefon ve bilgisayarda URL'yi gizli pencerede açıp çalıştığını doğrulayın.
6. Play Console → Politika ve programlar / Uygulama içeriği → Gizlilik politikası
   alanına gerçekten çalışan URL'yi yazın.
7. Oyunun Ayarlar menüsünde “Gizlilik Politikası / Privacy Policy” bağlantısını
   aynı URL'ye ekleyin. Google Play Veri Güvenliği beyanını da aynı gerçek
   veri işleme akışına göre doldurun.

## BİLMENİZ GEREKENLER

- Google Play, gizlilik politikası için erişilebilir, herkese açık, coğrafi
  kısıtlaması olmayan ve düzenlenemez HTTPS web sayfası ister; ZIP/PDF linki
  politikayı yayımlamanın yerine geçmez.
- Uygulamanız Firebase, Google Analytics, Crashlytics, Google Play Games,
  Google Sign-In, Google Play Billing, oyuncu hesapları, sunucu tabanlı çoklu
  oyuncu sistemi veya başka hizmet kullanıyorsa bu iki varsayılan metinden
  hiçbiri olduğu gibi yeterli olmayabilir. Verinin türü/amacı/alıcıları/
  saklama ve silme koşulları ilgili bölümlere eklenmelidir.
- Hesap oluşturuluyorsa Google Play'in hesap silme kuralları uygulanır;
  uygulama içi ve dışı silme yolu gerekebilir.
- Reklamlar gerçekten kullanılıyorsa veri kullanımı Google AdMob'un o günkü
  SDK davranışına ve rıza yönetimine göre denetlenmelidir.
- Reklamsız şablonda “veri toplanmaz” anlamına gelen ifadeler SDK olmadığını
  doğrulamadan kullanılmamalıdır.
- İletişim e-posta adresi herkese açık Victorium Soft Google Play sayfasındaki
  destek e-postasıdır; isterseniz yayın öncesi kontrol edip değiştirin.
- Bu içerik tek başına hukukî uygunluk veya Google Play kabul garantisi vermez.

## GOOGLE RESMÎ KAYNAKLARI

https://support.google.com/googleplay/android-developer/answer/10144311
https://support.google.com/googleplay/android-developer/answer/10787469
https://policies.google.com/privacy
