# Showgenda

TV Time benzeri, tarayıcıda çalışan dizi takip uygulaması.

**Adres:** https://showgenda.github.io/

## Neler var
- Google ile giriş; takip listesi bütün cihazlarda aynı
- Takip listesi, yaklaşan bölümler (yayın günü ve saatiyle), izlenen bölümler ve profil istatistikleri
- Dünyada trend diziler, "Senin için" önerileri ve benzer diziler
- Ülkeye göre izleme platformları ve aylık abonelik planı
- IMDb, Rotten Tomatoes, Metacritic ve Letterboxd puanları
- Oyuncular, yapım ekibi, kişi sayfaları ve "Tanıdık yüzler"
- Yetişme planı ve kaldığın dakika
- Yerli diziler için baştan sona bölüm numarası, fragman ve YouTube bağlantıları
- Arkadaşlarla ortak yorumlar ve puanlar; yorum bildirme ve yönetici denetimi

## Kullanım
Kurulum gerekmez; siteyi açıp Google hesabınla giriş yapman yeterli. TMDB ve MDBList anahtarları sunucuda durur, kodda gizli anahtar yoktur. Koddaki Supabase anahtarı, tarayıcıda kullanılmak üzere herkese açık olan "publishable" anahtardır.

## Veri kaynakları
Dizi bilgileri ve afişler [TVmaze](https://www.tvmaze.com) (CC BY-SA); trend, öneriler, oyuncu ve ekip bilgileri [TMDB](https://www.themoviedb.org); izleme platformları TMDB üzerinden JustWatch; puanlar [MDBList](https://mdblist.com); şarkı listeleri için [Tunefind](https://www.tunefind.com) bağlantıları. Bu ürün TMDB API'sini kullanır ancak TMDB tarafından onaylanmamıştır.
