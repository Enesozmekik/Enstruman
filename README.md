# Enstruman
Enstrüman Mağazası Otomasyon Yazılımı
Microsoft Visual Studio 2022 IDE kullanılmıştır
C# Windows Forms Uygulamasıdır

Proje Hakkında

Bu proje, müzik mağazaları veya enstrüman depoları için enstrüman türlerinin ve stok bilgilerinin yönetilmesini sağlayan basit bir otomasyon sistemidir.
 
 Kullanılan Teknolojiler
  -Programlama Dili: C# (Windows Forms)
  -Veritabanı: Microsoft Access (.accdb)
  -Bağlantı Sağlayıcı: OLEDB (Microsoft.ACE.OLEDB.12.0)

Aşağıdaki tablolar kullanılılarak Access VeriTabanı İskeleti olusturulmuştur:

kategori(Tablo)
 -ID (Number)
 -kategori (Text) – Örnek: Telli, Yaylı, Üflemeli

enstrumanturu(Tablo)
  -ID (Number)
  -enstrumanturu (Text) – Örnek: Gitar, Keman

enstrumanlar(Tablo)
  -ID (Number)
  -enstruman (Text) – Örnek: Klasik Gitar, Bas Klarnet

enstrumanstok(Table)
  -barkodno (Text)
  -kategori (Text)
  -enstrumantur (Text)
  -enstruman (Text)
  -rafno (Text)
  -adet (Number)
  -giriştarihi (Date)

kullanicibilgi(Tablo)
  -ID(Number)
  -adsoyad(Text)
  -sifre(Text)
  -görevi(Text)

---------------------------------------------
 Uygulama Özellikleri
    -Enstrüman kategorisi ve türü ekleme
    -Stok takibi ve giriş işlemleri
    -Kullanıcı girişi (görevli kontrolü yapılabilir)
    -Veri kayıt işlemleri (insert) üzerinden işlem
     -Görsel arayüz ile veri yönetimi


 Geliştiriciler
    -Enes Özmekik – Gazi Üniversitesi, Bilgisayar Mühendisliği

    -Sahra Dede – Gazi Üniversitesi, Bilgisayar Mühendisliği

    -Türkan Karabulut – Gazi Üniversitesi, Bilgisayar Mühendisliği

    


 


