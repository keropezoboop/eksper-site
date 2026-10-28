# Eksper konsept sitesi: yapılacaklar ve notlar

Durum: Test / sunum sayfası. Aşağıdakiler **Yaşar Bey kabul ederse** eklenecek.

## Yaşar Bey'e sorulacaklar

### A. Önce (her şeyden önce)
1. **Portföy izni:** "Bu çalışmayı adınızla portföyümde gösterebilir miyim?"

### B. İçerik
2. **Adres:** Sitede 28/G, iletişim sayfasında 28/C, Google Haritalar'da 28/H yazıyor. Doğrusu hangisi?
3. **WhatsApp:** 0543 838 16 32 WhatsApp'ta kullanılıyor mu? (Yeni sitede WhatsApp butonu var.)
4. **Ücretsiz değerleme** yapıyorlar mı? Yapıyorlarsa butona "Ücretsiz" yazılacak.
5. **İnşaat bakım onarım** hizmeti hâlâ veriliyor mu? (Eski logoda yazıyor.)
6. **Çalıştıkları semtler:** Değerleme formundaki semt listesi (Beşevler, Ataevler, Özlüce, Görükle) örnek olarak konuldu.
7. **Uzman gözü maddeleri:** Depreme dayanıklılık, TSE malzeme kontrolü, teknik inceleme, emsal değer. Onaylatılacak.
8. **Ofis telefonu:** (224) 443 43 41 hâlâ geçerli mi?

### C. Logo ve yönetim
9. **Logo:** Kırmızı-mavi logo yeni tasarıma uymuyor. Sade bir versiyon öner.
10. **Güncelleme:** "Siteyi kendiniz güncellemek ister misiniz (özellikle blog yazısı), yoksa değişiklikleri ben mi yapayım?" → Panel mi, aylık bakım mı?

### D. Teknik (yayına alma için)
11. **Alan adı:** "Alan adınızı hangi Gmail hesabıyla yönetiyorsunuz?" (Alan adı Squarespace'te kayıtlı; eskiden Google Domains'teydi, büyük ihtimalle Gmail ile giriliyor. Son kullanma: 12 Nisan 2027.) Değişikliği Yaşar Bey'in yanında, onun hesabından yap; şifre almaya gerek yok.
12. **Eski host:** "Sitenizi kim kurdu, barındırma için kime ve ne kadar ödüyorsunuz?" (Site, "Affordable Web Design" firmasının Liquid Web'deki sunucusunda: host2.affordablewebdesign.com. Eski masraf sunumda "yeni sistemde sıfır" diye kullanılabilir.)
13. **E-posta:** "@eksperbursaemlak.com uzantılı bir e-posta adresi kullanıyor musunuz?" (Alan adında Mailgun e-posta kaydı var. Kullanıyorsa taşımadan önce Gmail'e yönlendirme ayarlanacak, yoksa mailler kaybolabilir. Sadece Gmail kullanıyorsa bir şey yapmaya gerek yok.)

## Kabul edilirse eklenecek içerik (eski siteyle karşılaştırmadan)
- [ ] **Ofis telefonu:** (224) 443 43 41 (iletişim bölümüne)
- [ ] **"Tecrübe · Dürüstlük · Üstün Hizmet"** (eski sitedeki çalışma prensibi, tanıtım bölümüne)
- [ ] **"En iyi ve dürüst emlakçınız Bursa'da"** sloganını bir yerde kullanmayı değerlendir
- [ ] **Portföy kategorileri:** Konut · İşyeri · Arsa (· Bina) butonları, sahibinden mağaza linkleri:
  - Tüm ilanlar: https://bursaeksperemlak.sahibinden.com/emlak?sorting=date_desc
  - İşyeri: https://bursaeksperemlak.sahibinden.com/is-yeri?sorting=storeShowcase
  - Satılık daire: https://bursaeksperemlak.sahibinden.com/satilik-daire?sorting=storeShowcase
- [ ] **Formlar:** Eski sitedeki "Gayrimenkul Arıyorum" ve "Satmak / Kiralamak İstiyorum" formları. Değerleme formuna "Satmak / Almak / Kiralamak istiyorum" seçeneği olarak birleştirilebilir.
- [ ] **Form gerçekten çalışsın:** Gönderilen bilgiler Yaşar Bey'e e-posta veya WhatsApp ile ulaşmalı (şu an sadece görüntü).
- [ ] **Google yorumları linki** (eski sitede yorum isteme sayfası var: http://bit.ly/39Sci90)
- [ ] **Rehber:** Eski sitede 17 yazı var, galeride 5'i gösteriliyor. Öne çıkarılabilecekler:
  - Emlak alırken dikkat edilmesi gereken hususlar
  - Arazi alırken dikkat edilmesi gereken 8 önemli nokta
  - Bursa'da nasıl yatırım yapılır: emlak mı, arsa mı?
  - Emlak yatırımı neden altından daha iyi?
  - Kira sözleşmesi hangi durumlarda sona erer?
  - Bursa Nilüfer ilçemizi tanıyalım / Nilüfer mahalleleri
  - Neden gayrimenkul danışmanı ile çalışmalısınız?
- [ ] Rehber yazılarını yeni sitenin içine taşı (şu an eski siteye link veriyor).
- [ ] Kalan stok fotoğrafları değiştir (Satanlar için, Alanlar için, Rehber 1-2-5, uzman gözü şeritleri).
- [ ] Yayına alma (portföy için).

## Yönetim paneli (Yaşar Bey siteyi kendisi güncellemek isterse)
Görüşmede sor: **"Siteyi kendiniz güncellemek ister misiniz, yoksa değişiklikleri ben mi yapayım?"**
- **Karar:** WordPress yok (ne tam WordPress ne arka planda "headless" WordPress). Güncelleme ve güvenlik derdi, ek barındırma maliyeti istemiyoruz.
- **Yapılacak:** Hafif içerik paneli (Decap CMS / TinaCMS gibi). Site sabit kalır, `/admin` adresinden giriş yapılır.
- **Panelde düzenlenebilecekler:** Blog yazıları (başlık, kapak fotoğrafı, kısa özet, metin), fotoğraflar, temel metinler.
- **Düzenlenemeyecekler (bilerek):** Renkler, yazı tipleri, sayfa düzeni. Tasarım hep tutarlı kalır.
- **Blog yazısı akışı:** Panelde "Yeni Yazı" → formu doldur → "Yayınla". Yazı hazır yazı sayfası şablonuyla açılır ve ana sayfadaki Eksper Rehber galerisine kendiliğinden eklenir.
- [ ] Blog **yazı sayfası şablonunu** tasarla (sitenin tasarımıyla aynı: espresso, altın, aynı yazı tipleri).
- [ ] Eski sitedeki **17 blog yazısını** bu şablona taşı.
- [ ] Rehber galerisini son yazıları otomatik gösterecek hale getir.
- [ ] Paneli kur ve Yaşar Bey'e 10 dakikalık kullanım gösterimi yap.

## Yayına alma ve barındırma (eski sitenin yerine koymak)
Görüşmede sor: **"Alan adınız ve sitenizin barındırması kimin hesabında, şifresi kimde?"** (Siteyi başka biri kurduysa erişim/devir gerekebilir; en uzun sürebilecek kısım bu.)
- [ ] Siteyi ücretsiz sabit site barındırmasına koy (Netlify / Vercel / Cloudflare Pages), GitHub'a bağla.
- [ ] Taşımadan önce alan adının e-posta (MX) kayıtlarını kontrol et. (Gmail kullanıyorlar, büyük ihtimalle risk yok.)
- [ ] `eksperbursaemlak.com` alan adını yeni siteye yönlendir (DNS). Yayılması birkaç saat sürebilir.
- [ ] Blog yazılarını taşırken adresleri aynı tut (ör. `/bursa-kiralik-ev-ve-daire/`), Google sıralaması korunsun.
- [ ] Yeni site sorunsuz çalışınca eski WordPress barındırmasını iptal ettir (önce yenilenme tarihine bak).
- [ ] Sayfadaki `noindex` etiketini kaldır (şu an arama motorlarına kapalı).

## Fiyat notları (Ekim 2026 piyasa araştırması, kabaca gösterge)
- Bu müşteriye site **ücretsiz** (karşılığında portföy izni).
- **Yönetim paneli:** 2.000 TL, tek seferlik.
- **Aylık bakım:** 1.000 TL (alan adı ve barındırma dahil). Yıllık peşin: 10.000 TL. Kapsamı yazılı olarak netleştir: ayda birkaç küçük metin/fotoğraf değişikliği, yedekleme, sitenin ve formların çalışır durumda kalması.
- Sonraki müşterilerde özel tasarım siteyi 5.000 TL'ye satma. Piyasada bu kalitede işler 15.000 TL ve üzerinden başlıyor.
- Teklif verirken KDV dahil mi hariç mi netleştir.

## Sunumda kullanılacak bulgu
Eski sitedeki formların **hiçbiri çalışmıyor**: "Gayrimenkul Arıyorum" ve "Satmak / Kiralamak İstiyorum" sayfalarında form yerine `[gravityform ...]` kodu görünüyor, sayfa altlarındaki "Emlak Talep Formu" başlığının altı boş. Şu an siteden kimse ulaşamıyor, sadece telefonla ulaşılabiliyor.

## Bilinçli olarak eklenmeyenler
- Eski ana sayfadaki "dürüst iş yapan emlakçılar maalesef azdır" cümlesi (rakipleri kötüleyen dil).
- Yaşar Bey'in portresi (ortak kararla kaldırıldı).

## Fotoğraf kaynakları
Tüm fotoğraflar Unsplash'ten (Kerem'in seçtikleri: tanıtım, değerleme, Bursa sokak / tramvay / tarihi ev). Video: Kerem'in yüklediği stok video.
