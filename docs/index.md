# AĞ GÜVENLİĞİ STARTEJİLERİ VE UYGULAMALARI

Günümüzde kullanılan bilgi tabanlı sistemlerin güvenliğini sağlamak gelişen teknoloji ve dijitalleşme ile birlikte zor bir problem haline gelmiştir. Özellikle veritabanı yönetim sistemleri, hareketli araç ağları, bulut bilişim ve nesnelerin interneti gibi alanlarda bilgi güvenliği, gizlilik, bütünlük ve kullanılabilirlik gibi temel ilkelerle doğrudan ilişkilidir. Güvenliğin sağlanması, mevcut sistemlerin düzgün bir şekilde çalışabilmesi ve kullanıcılara kesintisiz bir hizmet sunabilmesi için çok önemlidir.

Bilgi tabanlı sistemlerin güvenli ve sürdürülebilir şekilde faaliyetine devam edebilmesi için bu sistemlere yönelik potansiyel saldırı çeşitlerini anlamak kritik bir öneme sahiptir. Bu raporun ana odak noktası söz konusu sistemlere ait temel özellikler ve işleyiş prensipleri üzerinde durularak bu sistemlere yönelik olası güvenlik tehditlerinin ele alınması ve bu güvenlik açıklarının kapatılması için en iyi uygulamaların açıklanmasıdır.

İncelenecek olan güncel ağ güvenliği sorunları üç ana başlık altında toplanmıştır:

* 1-DDoS Saldırıları
* 2-Veri İhlalleri
* 3-Diğer Güvenlik Tehditleri


## DDoS Saldırıları

In the digital age, the proliferation of technology has opened up new frontiers of connectivity and convenience. However, with these advancements comes the shadow of cyber threats, with Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks emerging as prominent disruptors. A distributed denial-of-service (DDoS) attack disrupts the operations of a server, service, or network by flooding it with unwanted Internet traffic. At their worst, these attacks can knock a website or entire network offline for extended periods of time.
Bu kısımda DDoS saldırılarının çalışma mekanizmaları, kullanılan stratejiler ve bu saldırılar karşısında alınabilecek önlemler açıklanacaktır.


### DDoS Saldırı Çeşitleri


#### Uygulama Katmanı Saldırıları:

DDoS saldırıları, çoğunlukla uygulama katmanında gerçekleşen Layer 7 DDoS saldırıları olarak tanımlanan türlerden oluşmaktadır. Bu saldırıların amacı hedefin ağ kaynaklarını ve sunucusunu meşru gibi görünen HTTP talepleri sayesinde aşırı yükleyerek bir hizmet reddi yaratmaktır.

#### Protokol Saldırıları:

Protokol saldırıları durum tükenme saldırıları olarak da adlandırılabilir. Protokol saldırıları, Layer 3 veya 4 protokollerini (örnek olarak ICMP) kullanarak altyapıyı ve ağ ekipmanını aşırı yükleyerek bir hizmet reddi yaratılmasını sağlar.