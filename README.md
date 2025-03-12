# Toprağın Nemini Ölçüp Bildiren Sistem

## 1. Proje Konusu
Toprağın nem seviyesi, bitkilerin sağlıklı büyümesi için önemli bir faktördür. Bu proje ile toprak nemini ölçen ve ölçülen verileri Telegram uygulaması üzerinden kullanıcılara bildirim gönderen bir sistem tasarlanacaktır. Bu sayede bitki bakımı kolaylaşacak ve sulama zamanları hatırlatılacaktır .

## 2. Proje Kısa Özeti
Bu projede bir toprak nem sensörü kullanılarak nem seviyeleri Arduino tarafından okunacak ve belirlenen aralıklarla (4 saatte bir) Telegram botu aracılığıyla kullanıcılara bildirim olarak iletilecektir. Arduino’nun internet bağlantısı için ESP8266 veya ESP32 modülü kullanılacaktır.

## 3. Proje Gereksinimleri
Projeyi çalıştırmak için aşağıdaki bileşenler gereklidir:
- *Donanım:*
  - Arduino (UNO, Mega, vb.)
  - Toprak nem sensörü
  - ESP8266 veya ESP32 Wi-Fi modülü
  - Jumper kablolar
- *Yazılım:*
  - Arduino IDE
  - Telegram Bot API
  - ESP8266WiFi veya WiFi kütüphanesi
  - ArduinoJson kütüphanesi

## 4. Projeyi Çalıştırma
### 4.1 Donanım Bağlantıları
1. Toprak nem sensörünü Arduino'nun analog girişine bağlayın.
2. ESP8266 veya ESP32 modülünü Arduino’ya bağlayarak internet bağlantısını sağlayın.

### 4.2 Yazılım Kurulumu
1. *Arduino IDE'yi yükleyin* ve ESP8266/ESP32 için gerekli kütüphaneleri ekleyin.
2. *Telegram botu oluşturun* ve bot token’ınızı alın.
3. Aşağıdaki komutları kullanarak gerekli kütüphaneleri yükleyin:
   cpp
   #include <ESP8266WiFi.h> // ESP32 kullanıyorsanız WiFi.h
   #include <ArduinoJson.h>
   
4. Arduino kodunu derleyip yükleyin.
5. Cihazınızı açarak Telegram üzerinden bildirimleri almaya başlayın.

## 5. Proje Lisans Bilgileri
Bu proje MIT Lisansı ile lisanslanmıştır. Serbestçe kullanabilir, değiştirebilir ve dağıtabilirsiniz.

## 6. Proje Anahtar Kelimeleri
- Arduino
- Toprak Nem Sensörü
- ESP8266 / ESP32
- Telegram Bot API
- IoT (Nesnelerin İnterneti)
- Otomatik Sulama Sistemi
