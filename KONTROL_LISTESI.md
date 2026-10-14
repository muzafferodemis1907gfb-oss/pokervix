# Google Play – POKERVIX Poker veri güvenliği kontrol listesi

Bu belge **cevap anahtarı değildir**. Uygulamanın gerçek sürümünü inceleyerek doldurun.

- [ ] Oyunda Google AdMob / reklam SDK'sı var mı?
- [ ] AndroidManifest.xml'de `com.google.android.gms.permission.AD_ID` var mı?
- [ ] Reklam SDK'sı reklam kimliği, IP, cihaz bilgisi, tanılama, etkileşim verisi işliyor mu?
- [ ] Firebase Analytics veya Crashlytics var mı?
- [ ] Google Play Games oturum açma, profil, başarı, liderlik tablosu var mı?
- [ ] Çok oyunculu çevrimiçi oyun, sohbet, oyuncu hesabı, sunucu var mı?
- [ ] E-posta, takma ad, profil fotoğrafı, kullanıcı ID gibi bilgilerin kaydı var mı?
- [ ] Oyun içi satın alma veya ödeme entegrasyonu var mı?
- [ ] Uygulama fotoğraf, mikrofon, konum veya başka hassas izinler kullanıyor mu?
- [ ] Oyun kayıtları cihazdan dışarı aktarılıyor ya da buluta yedekleniyor mu?
- [ ] Saklama ve silme süreleri doğru açıklanıyor mu?
- [ ] Reklamlar için gereken bölgelerde geçerli rıza yönetimi var mı?
- [ ] Uygulamanın Play Console 'Veri güvenliği' cevapları politikayla tutarlı mı?
- [ ] Uygulama içindeki gizlilik bağlantısı gerçekten açılıyor mu?
- [ ] Web adresi giriş gerektirmeden, her ülkeden ve cihazdan açılabiliyor mu?
- [ ] Politikada geliştirici adı, uygulama adı, iletişim ve güncelleme tarihi var mı?

**UYARI:** Bu sorulardan herhangi birinde mevcut şablondan farklı uygulama
akışı tespit edilirse metni buna göre düzenleyin; özellikle SDK'lar önemlidir.
