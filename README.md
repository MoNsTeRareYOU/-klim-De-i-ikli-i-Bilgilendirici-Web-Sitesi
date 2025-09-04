İklim360 🌍 — Kısa Sunum Notları
================================

Giriş
- Merhaba, ben … Bugün size iklim değişikliği hakkında hazırladığım web sitesini tanıtacağım. Hedefim: anlaşılır bilgi + hemen uygulanabilir öneriler. Site açık/karanlık tema ve akıcı animasyonlarla izlemeyi kolaylaştırıyor.

Problem ve Neden Önemli?
- İklim değişikliği; sağlık, su, tarım ve ekonomi üzerinde etkili. Aşırı hava olayları sıklaşıyor, maliyet artıyor. Bu yüzden önce “Nedir?” ve “Neden Önemli?” bölümleriyle zemini hızlıca kuruyoruz.

Proje Özeti
- Yapı: Düz HTML/CSS/JS. Tema değiştirici (🌞/🌙), sayfa geçişlerinde fade, scroll‑reveal ve “Yukarı dön” ile rahat kullanım. Kartlar hover ile canlanıyor.
- İçerik: “Çözümler” kısmında enerji‑ulaşım‑tüketim önerileri ve “Hemen Atılacak Adımlar” listesi. “Karbon Ayak İzi” sayfasında basit bir hesaplayıcı ile anlık, emojili geri bildirim.

Kısa Demo Akışı
- 1) Tema değiştir → kontrast farkını göster.
- 2) Nedir? → sera etkisi/insan etkisi kartları.
- 3) Etkiler → sağlık ve su örnekleri.
- 4) Çözümler → kart hover + “Hemen Atılacak Adımlar”.
- 5) Karbon Ayak İzi → seçimleri değiştir, sonuç anında güncellensin.
- 6) Kaynaklar → IPCC/UN/NASA bağlantıları.

Teknik Kısa Bilgi
- Tema durumu `localStorage`’da, geçişler küçük JS fonksiyonlarıyla. CSS değişkenleri ve grid yapısı ile responsive tasarım.

Sonuç ve Kapanış
- İklim360; kavramları netleştiriyor, etkileri görünür kılıyor ve eylem öneriyor. Hedefim: bilgilendirirken harekete geçirmek. Teşekkürler — sorularınızı alabilirim.

Nedir? ❓
---------
- İklim değişikliği hakkında basit, anlaşılır ve etkileyici bir bilgilendirme sitesi.
- Hızlı okunur; animasyonlar, tema değişimi ve pratik öneriler var.

Öne Çıkanlar ✨
--------------
- Tema: 🌞/🌙 tek tıkla açık/karanlık mod (tercih kaydedilir).
- Geçişler: Sayfalar arası yumuşak fade; bölümler scroll ile belirir.
- Hesaplayıcı: “Karbon Ayak İzi” sayfasında basit seçimlerle anlık sonuç (emojili).
- Mobil uyum: Sticky header, “Yukarı dön” butonu, grid kartlar.

Sayfalar 🧭
-----------
- Nedir? • Neden Önemli? • Etkiler • Çözümler • Karbon Ayak İzi • Kaynaklar
- Kısa kartlar + net listeler. Sunumda akıcı ilerlemek için ideal.

Sunum Akışı 🎤
--------------
1) Anasayfa başlığı ve tema değişimi.
2) “Nedir?” kartları ve 1–2 “yanlış bilinen”.
3) “Etkiler”den sağlık/su örneği.
4) “Çözümler” ve “Hemen Atılacak Adımlar”.
5) Karbon hesaplayıcıda seçenek değiştirip sonucu göster.
6) Kaynaklar ile bitir, soru‑cevap.

Nasıl Çalıştırırım ⚙️
--------------------
- `python main.py` → `http://127.0.0.1:8000/`
- Alternatif: VS Code Live Server ile `index.html`.

Teknik Kısa Bilgi 🧩
-------------------
- Düz HTML/CSS/JS. Tema toggle, fade geçiş, scroll‑reveal, aktif menü, “yukarı dön”, hesaplayıcı.
- `test.txt` içinde kısa manuel test listesi var.

Özelleştirme 🎯
--------------
- Renkler: `style.css` içindeki `:root` ve `body.light`.
- Metin/içerik: HTML’deki kart ve listeleri düzenle.
- Görseller: `assets/` içindeki JPEG’ler (boyutlar width/height ile sabitlenmiş).
