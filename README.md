# OSİ Referans Modeli

OSİ (Open Systems Interconnection) referans modeli, bilgisayar ağlarındaki iletişimi standartlaştırmak ve farklı ağ protokollerinin birbirleriyle uyumlu bir şekilde çalışmasını sağlamak amacıyla geliştirilen bir referans modelidir. ISO (International Organization for Standardization) tarafından 1984 yılında tanıtılmıştır. Bu model, ağların farklı katmanlara ayrılması ve her katmanın belirli görevleri üstlenmesi ilkesine dayanır.


| Katman   | İşlev                                                            | Protokoller                                                       |
|----------|------------------------------------------------------------------|-------------------------------------------------------------------|
| Uygulama | Kullanıcı uygulamalarıyla doğrudan etkileşim ve veri alışverişi  | HTTP, SMTP, FTP, DNS, SSH, DHCP, SNMP, POP3, IMAP, Telnet, HTTPS  |
| Sunum    | Veri temsili, şifreleme, sıkıştırma ve protokol dönüşümleri      | JPEG, GIF, MPEG, SSL, TLS, ASCII, UTF-8, PNG                      |
| Oturum   | Uygulamalar arasında oturum yönetimi                             | NetBIOS, RPC, SSH, TLS Handshake,SCP, Telnet Negotiation          |
| Taşıma   | Veri akış kontrolü ve güvenilir veri iletimi                     | TCP, UDP, SCTP                                                    |
| Ağ       | Yönlendirme ve paketleme işlemleri                               | IPv4, IPv6, ICMP, OSPF, BGP, RIP, ARP                             |
| Datalink | Fiziksel adresleme, hata kontrolü ve erişim kontrolü             | Ethernet, PPP, HDLC, IEEE 802.11, Frame Relay                     |
| Fiziksel | Verilerin fiziksel ortama aktarılması                            | Ethernet, USB, RS-232, Bluetooth, Wi-Fi, Fiber Optik, DSL         |



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

