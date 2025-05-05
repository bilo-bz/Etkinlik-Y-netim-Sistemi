# Etkinlik Yönetim Sistemi

> Etkinlik yönetim sistemi sayesinde yeni etkinlik ekleyebilir, yeni katılımcı ekleyebilir, bilet oluşturabilir biletleri eklediğimiz katılımcılara satabiliriz.

# ▶︎ Etkinlikler Kısmı:

Bu bölümde yeni etkinlik oluşturabiliriz. 
Etkinlik oluşturulurken önce etkinliğin adı sonra etkinliğin tarihi, etkinlik yapılacağı yer ve etkinliğin kapasitesi belirtilmelidir.
Tüm bu gerekenler belirtildikten sonra "Etkinlik Ekle" butonuna basarak etkinliği ekleyebiliriz.

Etkinlik ekle butonunun alt tarafında daha önceden eklediğimiz etkinlikleri görüntüleyebiliyoruz. 
Eğer istersek daha önceden eklediğimiz etkinlikleri seçerek "Etkinliği Sil" butonuna basabilir ve etkinliği silebiliriz.

![image](https://github.com/user-attachments/assets/92328539-c940-4e5d-a3f1-92669e70d23c)

▶︎ "test" adında bir etkinlik ekliyoruz. Etkinliğin toplam kapasitesini ve satılan bilet sayısını görebiliyoruz. Bu etkinliğin mevcut etkinlikler kısmındaki görünümü şu şekildedir.

![image](https://github.com/user-attachments/assets/fb7812a1-900d-45b1-924c-a78c37fd7f2b)

# ▶︎ Katılımcılar Kısmı:

Katılımcılar bölümünde ise bilet satılabilecek katılımcıları ekleyebiliyoruz. Eklemek istediğimiz katılımcının adını soyadını ve iletişim adresini (telefon numarası veya mail adresi) olacak şekilde ekliyoruz.

Eklediğimiz katılımcıyı "Katılımcı Ekle" butonunun altındaki **Mevcut Katılımcılar** bölümünden görüntüleyebiliyoruz.

![image](https://github.com/user-attachments/assets/4d32ab3c-dc61-42e6-911c-ee7b08d164eb)

# ▶︎ Biletler Kısmı:

Bilet oluşturmak için daha önceden bir etkinlik eklemiş olmamız gerekmektedir.

Eklediğimiz etkinliği seçerek bilet fiyatı kısmına biletin adet fiyatının ne kadar olmasını istiyorsak yazıyoruz. 

Fiyatı yazdıktan sonra bileti oluşturmak için "Seçili Etkinlik İçin Biletleri Oluştur" butonuna basıyoruz ve biletimiz oluşuyor.

# ▶︎ Bilet Satışı:

Bilet oluşturduktan sonra, daha önceden oluşturduğumuz katılımcılardan herhangi birini seçerek ve satmak istediğimiz bileti satarak biletleri satabiliyoruz.

![image](https://github.com/user-attachments/assets/571bef48-e53f-4fc7-bbb0-78e9154bd366)


# ▶︎ Programdaki Veriler
Veriler her işlem yapıldığında kaydedilmektedir. Bu verileri programın çalıştığı klasörün içerisine "biletler.json", "etkinlikler.json", "katilimciler.json" olarak ayrı ayrı kaydetmektedir. Program başlatıldığında otomatik olarak bu dosyalardan kayıtları çekmekte ve programa entegre etmektedir.


# ▶︎ Proje nasıl çalıştırılır?

1) Visual studio code uygulamasını indirip eklentiler kısmından Python eklentisini kurun.
2) Projeyi indirin ve herhangi bir klasöre çıkartın.
3) Çıkarttıktan sonra etkinlik_yonetim adındaki dosyayı visual studio code kullanarak açın.
4) Sağ üst kısımdan (oynatma tuşu) başlat tuşuna basarak projeyi çalıştırabilirsiniz.
   
