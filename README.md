# DNS-Temizleyici

**DNS-Temizleyici**, Windows işletim sistemlerinde DNS önbelleğini temizlemek, IP adreslerini serbest bırakmak ve yenilemek için kullanılan basit bir batch scriptidir.

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
