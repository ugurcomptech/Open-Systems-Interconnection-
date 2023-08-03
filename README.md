# OSİ Referans Modeli

OSİ (Open Systems Interconnection) referans modeli, bilgisayar ağlarındaki iletişimi standartlaştırmak ve farklı ağ protokollerinin birbirleriyle uyumlu bir şekilde çalışmasını sağlamak amacıyla geliştirilen bir referans modelidir. ISO (International Organization for Standardization) tarafından 1984 yılında tanıtılmıştır. Bu model, ağların farklı katmanlara ayrılması ve her katmanın belirli görevleri üstlenmesi ilkesine dayanır.


| Katman      | İşlev                      | Protokoller                          |
|-------------|----------------------------|--------------------------------------|
| Uygulama    | Kullanıcı uygulamalarıyla   | HTTP, SMTP, FTP, DNS, SSH, DHCP,     |
|             | doğrudan etkileşim         | SNMP, POP3, IMAP, Telnet, HTTPS     |
|             | ve veri alışverişi         |                                      |
|-------------|----------------------------|--------------------------------------|
| Sunum       | Veri temsili, şifreleme,   | JPEG, GIF, MPEG, SSL, TLS,           |
|             | sıkıştırma ve protokol     | ASCII, UTF-8, PNG                   |
|             | dönüşümleri                |                                      |
|-------------|----------------------------|--------------------------------------|
| Oturum      | Uygulamalar arasında       | NetBIOS, RPC, SSH, TLS Handshake,    |
|             | oturum yönetimi            | SCP, Telnet Negotiation              |
|-------------|----------------------------|--------------------------------------|
| Taşıma      | Veri akış kontrolü ve      | TCP, UDP, SCTP                      |
|             | güvenilir veri iletimi     |                                      |
|-------------|----------------------------|--------------------------------------|
| Ağ         | Yönlendirme ve paketleme   | IPv4, IPv6, ICMP, OSPF, BGP,        |
|             | işlemleri                  | RIP, ARP                            |
|-------------|----------------------------|--------------------------------------|
| Datalink    | Fiziksel adresleme,        | Ethernet, PPP, HDLC, IEEE 802.11,   |
|             | hata kontrolü ve erişim   | Frame Relay                         |
|             | kontrolü                   |                                      |
|-------------|----------------------------|--------------------------------------|
| Fiziksel    | Verilerin fiziksel         | Ethernet, USB, RS-232, Bluetooth,   |
|             | ortama aktarılması         | Wi-Fi, Fiber Optik, DSL             |
|             |                            |                                      |



## Fiziksel Katman (Physical Layer)

Fiziksel katman, verilerin ağ üzerindeki fiziksel ortamdan aktarılmasından sorumludur. Elektrik sinyalleri, radyo dalgaları veya optik sinyaller gibi fiziksel medya kullanarak verileri bit akışlarına dönüştürür. Bu katmanı temsil etmek için, bir bilgisayar ağındaki kabloları ve bağlantıları gösteren bir diyagram kullanılabilir.

## Datalink Katman (Data Link Layer)

Datalink katmanı, fiziksel katmanın üzerine kurulur ve verilerin doğrudan komşu cihazlar arasında güvenli bir şekilde iletilmesini sağlar. Bu katmanda, verileri çerçeve olarak adlandırılan küçük parçalara böler ve hata kontrolü yaparak doğru iletimini sağlar. İki cihaz arasındaki veri çerçevelerinin aktarımını gösteren bir diyagram kullanılabilir.

## Ağ Katmanı (Network Layer)

Ağ katmanı, verilerin kaynak ve hedef cihazlar arasında nasıl iletilmesi gerektiğini belirler ve yönlendirme işlemlerini gerçekleştirir. Bu katmanda, IP adresleri gibi mantıksal adresleme kullanılır ve rota seçimi yapılır. Veri paketlerinin farklı ağlara yönlendirilmesini gösteren bir diyagram kullanılabilir.

## Taşıma Katmanı (Transport Layer)

Taşıma katmanı, kaynak ve hedef uygulamalar arasında veri akışını yönetir. Veri bütünlüğünü sağlamak için hata kontrolü ve akış kontrolü mekanizmalarını içerir. Bu katman, TCP (Transmission Control Protocol) ve UDP (User Datagram Protocol) gibi protokolleri kullanarak verilerin iletimini yönetir. Veri akışını temsil eden bir diyagram kullanılabilir.

## Oturum Katmanı (Session Layer)

Oturum katmanı, iki uygulama arasında sürekli bir iletişim oturumu oluşturmayı sağlar. Gerekliyse oturumun güvenliğini sağlar ve oturum yönetimi işlemlerini gerçekleştirir. İki uygulama arasındaki oturumu temsil eden bir diyagram kullanılabilir.

## Sunum Katmanı (Presentation Layer)

Sunum katmanı, verilerin farklı formatlardan bir diğerine dönüştürülmesini sağlar. Verilerin şifrelenmesi ve sıkıştırılması gibi işlemleri bu katmanda gerçekleştirilir. Farklı veri formatlarının sunum katmanı aracılığıyla nasıl dönüştürüldüğünü gösteren bir diyagram kullanılabilir.

## Uygulama Katmanı (Application Layer)

Uygulama katmanı, kullanıcıların ağ hizmetlerine erişmesini sağlar. E-posta, web tarayıcıları, dosya transferi ve diğer uygulamalar bu katmanda çalışır. Farklı uygulamalar arasındaki iletişimi temsil eden bir diyagram kullanılabilir.

