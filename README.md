# Hastane Otomasyonu Uygulaması Kurulum Kılavuzu

Bu kurulum kılavuzu, hastane otomasyonu uygulamasını yerel bir bilgisayara kurmak için adımları içermektedir.

## Önemli Notlar

- Bu kurulum kılavuzu, uygulamanın doğru çalışması için gereken adımları içermektedir. Lütfen adımları dikkatlice takip ediniz.
- Kurulum öncesinde bilgisayarınızda SQL Server'ın yüklü olması gerekmektedir. Ayrıca, gerekli SQL veritabanı dosyalarının bulunduğundan emin olunuz.

## Kurulum Adımları

1. `text.txt` dosyasını açın.
2. `Data Source=DESKTOP-FGVIOT1;Initial Catalog=hastaneProje;Integrated Security=True` satırında bulunan `DESKTOP-FGVIOT1` kısmını, kendi SQL Server adınızla değiştirin.
3. Değişiklikleri kaydedin ve `text.txt` dosyasını `C:\` klasörüne kopyalayın. (**Not:** Bu adımı atlamayın, aksi takdirde program çalışmaz.)
4. Başlat menüsünden "Hizmetler"i arayın ve açın. Burada SQL Server'ı bulun, sağ tıklayarak durdurun.
5. SQL klasöründeki SQL veritabanı tablolarını kopyalayın ve bilgisayarınızdaki SQL'in `data` klasörüne yapıştırın.
6. Bilgisayarınızda kurulu olan SQL Server'ı açın. Databases'e sağ tıklayın ve "Attach" seçeneğini seçin.
7. Açılan ekranda "Add" seçeneğini belirleyin ve kopyaladığınız SQL tablo ismini bulup seçin.
8. İşlemi onaylayın ve kurulum tamamlanmış olacaktır.

## Kurulum Sonrası

Yukarıdaki adımları tamamladıktan sonra uygulamayı kullanmaya başlayabilirsiniz. Herhangi bir sorunla karşılaşırsanız, lütfen [destek ekibiyle iletişime geçin](mailto:yakalan6@gmail.com).

---
**Not:** Bu README dosyası, kurulum sürecini adım adım açıklamak amacıyla oluşturulmuştur. Kurulum sırasında herhangi bir aksaklık yaşarsanız, ilgili adımları tekrar gözden geçirin veya geliştirici ekiple iletişime geçin.
