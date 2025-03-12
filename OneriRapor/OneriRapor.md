## TOPRAĞIN NEMİNİ ÖLÇÜP BİLDİREN SİSTEM

## Projenin Amacı ve Hedefi:

Toprağın nem seviyesi, bitkilerin sağlıklı büyümesi için önemli bir faktördür. Bu proje ile toprak
nemini ölçen, ölçülen verileri Telegram uygulaması üzerinden istenilen kullanıcılara bildirim gönderen bir sistem tasarlanacaktır. Bu sayede, bitki bakımı kolaylaştırılacak ve sulama zamanları
hatırlatılacaktır.

## Kullanılacak Yöntemler ve Teknolojiler:

1)Arduino Platformu: Proje, Arduino mikrodenetleyicisi kullanılarak geliştirilecektir.

2)Toprak Nem Sensörü: Toprak nemini ölçmek için gerekli nem ölçer sensörler kullanılabilir. Bu sensörler topraktaki nem seviyesini ölçerek, analog sinyal olarak Arduino'ya iletir.

3)Telegram Bot API: Telegram üzerinden bildirim gönderebilmek için bir Telegram botu oluşturulacaktır ve Telegram API kullanılarak Arduino ile entegrasyonu sağlanacaktır.

Arduino, belirli aralıklarla (4 saatte bir) sensör verilerini alacak ve Telegram API aracılığıyla kullanıcılara bildirim gönderecektir.

4)Ardunio ile iletişim ve Bildirim Gönderme: Arduino'nun internet erişimi sağlamak için bir ESP8266 veya ESP32 modülü kullanılacaktır. Bu modül, Arduino'nun Telegram API ile iletişim kurmasını sağlayacak ve verileri Telegram botuna gönderecektir. Bu sayede belli aralıklarla(4 saatte bir) nem bilgisini alabileceğiz.

## Proje Adımları:

Adım 1: Sensör Entegrasyonu: Toprak nem sensörü Arduino'ya bağlanarak veriler okunacaktır.

Adım 2: Telegram Botu: Telegram botu oluşturulacak, Telegrm API Arduino'ya entegre edilecektir.

Adım 3: Zaman Aralığı: Arduino, 4 saat arayla toprak nemini ölçüp Telegram'a gönderecek şekilde programlanacaktır.

Adım 4: Bildirim Sistemi: Nem seviyesi 4 saatte bir Telegram üzerinden bildirim olarak gönderilecektir.

Adım 5: Test ve Sonuç: Sistem test edilip, doğruluğu kontrol edilecek ve geri bildirimlere göre düzenlemeler yapılacaktır.
                  
                  
                  21360859018       21360859016         21360859015        21360859008
                  İrem Aytaş        Ahmet Mert Yıldız   İsa Caner Çal      Samet Dönmez
