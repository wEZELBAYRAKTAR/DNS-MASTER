# DNS-MASTER

[DNS Master](https://github.com/user-attachments/assets/d6221568-dbbb-4ea1-a6f6-8c1f833fc92b)

**DNS-MASTER**, Windows işletim sistemlerinde ağ bağlantı sorunlarını gidermek için kullanılan basit ve etkili bir batch scriptidir. Bu script, DNS önbelleğini temizleyerek, IP adreslerini serbest bırakıp yenileyerek ağ bağlantısını sıfırlar ve kullanıcıya işlem tamamlandığında bilgilendirici mesajlar sunar. Özellikle internet bağlantısında yaşanan gecikme, erişim sorunları veya DNS ile ilgili hatalar için hızlı bir çözüm sağlar.

## Özellikler
- DNS önbelleğini temizleme
- IP adreslerini serbest bırakma ve yenileme
- Kullanıcı dostu mesajlar ile bilgilendirme

## Kullanım

1. **Dosyayı İndirin:**
   Repository'yi klonlayabilir veya [buradan](https://github.com/wEZELBAYRAKTAR/DNS-MASTER/) indirebilirsiniz.

   ```bash
   git clone https://github.com/kullanici-adi/DNS-Temizleyici.bat

   Scripti Çalıştırın: İndirilen klasörde dns-temizleyici.bat dosyasına çift tıklayarak scripti çalıştırabilirsiniz.

   @echo off
   
DNS önbelleğini temizler
ipconfig /flushdns

IP adresini serbest bırakır
ipconfig /release

Yeni IP adresi alır
ipconfig /renew

Ekranı temizler
cls

Kullanıcıya bilgi verir
echo DNS Cache Temizleme yapildi.
echo Cikis icin herhangi bir tusa basiniz.
echo wEZELBAYRAKTAR iyi gunler diler.

Kullanıcının bir tuşa basmasını bekler
pause


Bu basit kodlamalar DNS Cache Temizlemek için en hızlı ve kolay olsun diye hazırlanmıştır, webmasterlar için oldukça işlevsel ve basit tutulmuştur.
