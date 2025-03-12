Movies App

Bu proje, React kullanılarak geliştirilen bir film keşif uygulamasıdır. Kullanıcılar The Movie Database (TMDb) API'sini kullanarak film arayabilir, film detaylarını görüntüleyebilir ve seçtikleri filmleri listeleyebilirler.

Özellikler

Film Arama: Kullanıcılar arama çubuğuna film ismi girerek TMDb API üzerinden film arayabilir.

Film Listesi: Arama sonucunda bulunan filmler listelenir ve her filme tıklayarak detayları görüntülenebilir.

Film Detayları: Seçilen filmin adı, posteri, açıklaması, çıkış tarihi ve puanı gibi bilgileri gösterir.

Dinamik Kullanıcı Arayüzü: React Hooks (useState, useEffect) kullanılarak oluşturulmuş dinamik bir bileşen yapısı.

Bootstrap Entegrasyonu: Kullanıcı dostu bir arayüz sağlamak için Bootstrap CSS sınıfları kullanılmıştır.

Kullanılan Teknolojiler

React.js - Bileşen bazlı UI geliştirme

Bootstrap - Şık ve duyarlı tasarım için

TMDb API - Film verilerini almak için

Kurulum

Bu projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1. Depoyu Klonlayın

git clone https://github.com/Gokeryldz/movies-app.git
cd movies-app

2. Bağımlılıkları Yükleyin

npm install

3. Çalıştırın

npm start

Bu komut, projeyi yerel geliştirme sunucusunda çalıştıracaktır. Tarayıcınızda http://localhost:3000 adresine giderek uygulamayı görebilirsiniz.

API Kullanımı

Bu proje, The Movie Database (TMDb) API kullanılarak film verilerini çekmektedir. API anahtarınızı App.js içinde api_key değişkenine eklemeniz gerekmektedir:

const api_key = "YOUR_API_KEY";

API anahtarınızı almak için TMDb'nin resmi web sitesinden kayıt olabilirsiniz.

Proje Yapısı

movies-app/
│── src/
│   ├── components/
│   │   ├── Nav.js
│   │   ├── Main.js
│   │   ├── MovieListContainer.js
│   │   ├── MovieDetails.js
│   │   ├── MyMovieList.js
│   │   ├── Footer.js
│   ├── App.js
│   ├── index.js
│── public/
│── package.json
│── README.md

App.js: Ana bileşen, arama sorgusunu ve seçilen filmi yönetir.

Nav.js: Kullanıcıların film arayabileceği navigasyon bileşeni.

Main.js: Ana içerik alanını yönetir ve MovieListContainer ve MovieDetails bileşenlerini içerir.

MovieListContainer.js: Aranan filmlerin listesini görüntüler.

MovieDetails.js: Seçilen filmin detaylarını gösterir.

MyMovieList.js: Kullanıcının favori filmlerini listeleyebilir (Gelecekte genişletilebilir).

Footer.js: Sayfa alt bilgisi.

Katkıda Bulunma

Projeye katkıda bulunmak isterseniz, pull request açabilirsiniz. Geliştirme için şu adımları takip edebilirsiniz:

Fork yapın.

Yeni bir branch oluşturun.

Değişikliklerinizi yapın ve commit edin.

Pull request gönderin.

Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına göz atabilirsiniz. 


Hazırlayan: Göker Yıldız


Eğer projeyle ilgili sorularınız veya önerileriniz varsa, benimle LinkedIn üzerinden iletişime geçebilirsiniz. 🚀


PROGRAMIN İÇİNDEN EKRAN GÖRÜNTÜSÜ

<img width="1678" alt="Ekran Resmi 2025-03-13 01 24 24" src="https://github.com/user-attachments/assets/f54720da-0a47-4a9a-9eab-16f8c6610816" />
<img width="1680" alt="Ekran Resmi 2025-03-13 01 33 30" src="https://github.com/user-attachments/assets/12b608c2-6e0c-40e1-9bb8-f83a6f12f9b3" />
<img width="1680" alt="Ekran Resmi 2025-03-13 01 35 00" src="https://github.com/user-attachments/assets/303df3bc-fbf1-4002-a0fa-d5e4ca2ffc8f" />


