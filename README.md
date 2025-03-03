# FilmRuhu: Ruh Haline Göre Film Önerileri

FilmRuhu, kullanıcıların ruh hallerine göre film önerileri sunan, modern ve dinamik bir web uygulamasıdır. Proje, TMDB API'sini kullanarak güncel film verilerini çeker ve kullanıcının seçimine göre çeşitli modlar (örneğin, "Mutlu 😊", "Hüzünlü 😢", "Aksiyon 🔥", vb.) üzerinden film önerileri sunar. Uygulama, kullanıcı dostu arayüzü, etkileyici animasyonları ve karanlık teması ile dikkat çekiyor.

---

## Özellikler

- **Ruh Hali Tabanlı Film Önerileri:** 
  - 15 farklı mod seçeneği sayesinde kullanıcının ruh haline uygun film önerileri sunulur.
  - Mod seçimi esnasında, her mod için TMDB API üzerinden birden fazla sayfadan veri çekilerek yaklaşık 100 film arasında gezinme imkanı sağlanır.

- **Dinamik Film Kartları:**
  - Film detayları (poster, başlık, tam özet, çıkış tarihi, puan) ana ekranda sabit olarak görüntülenir.
  - Film kartlarında, puanlar tek ondalık basamakla yuvarlanarak okunabilir bir formatta (örneğin, "4.7/10") sunulur.
  - Çıkış tarihi, "25 Temmuz 2024" gibi okunabilir bir formatta gösterilir.

- **Etkin Fragman İzleme Deneyimi:**
  - "Fragmanı İzle" butonuna tıklayınca, arka plan bulanıklaştırılarak modern bir modal pencerede fragman görüntülenir.
  - Fragman verileri TMDB API üzerinden çekilir; eğer fragman bulunamazsa kullanıcıya hata mesajı gösterilir.
  - Fragmanın hangi platformda (örneğin, YouTube) yayınlandığı bilgisi de ekranda yer alır.

- **Navigasyon & Kullanıcı Etkileşimi:**
  - "Önceki", "Sonraki" ve "Karıştır" butonları sayesinde kullanıcılar geniş film verisi içinde kolayca gezinebilir.
  - Beğeni/Düşen butonları, kullanıcıların film hakkında anlık geri bildirim vermesine olanak tanır.

- **Modern ve Duyarlı Tasarım:**
  - Sadece karanlık tema kullanılarak şık ve odaklanmış bir kullanıcı deneyimi sunulur.
  - Responsive (duyarlı) tasarım sayesinde, uygulama her cihazda (masaüstü, tablet, mobil) sorunsuz çalışır.
  - Metin tabanlı, fontlu bir logo ve modern bir navbar ile tamamlayıcı bir arayüz oluşturulur.
  - Footer kısmında, proje ismi, telif hakkı bilgileri ve sosyal medya linkleri yer alır.

---

## Teknoloji ve Araçlar

- **Frontend:** HTML5, CSS3, Vanilla JavaScript, Bootstrap 5  
- **API:** TMDB (The Movie Database) API  
- **Tasarım:** Karanlık tema, modern UI/UX prensipleri  
- **Ekstra:** FontAwesome (sosyal medya ikonları)

---

## Neden FilmRuhu?

FilmRuhu, kullanıcıların o anki ruh haline uygun film önerileri sunarak, film seçiminde kişiselleştirilmiş bir deneyim yaşatır. Geniş film veri tabanı ve dinamik TMDB entegrasyonu ile, her zaman güncel ve ilgi çekici içerikler sunar. Modern tasarımı, etkileşimli navigasyon butonları ve etkileyici fragman izleme deneyimi sayesinde film severlerin dikkatini çeker.

Bu proje, hem film öneri sistemlerine ilgi duyan geliştiriciler hem de modern web teknolojilerini kullanmak isteyenler için harika bir örnektir.

---

FilmRuhu ile film dünyasına yepyeni bir soluk getirin!
