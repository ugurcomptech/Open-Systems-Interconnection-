## Taşıma Katmanı (Transport Layer)

Taşıma Katmanı (Transport Layer), kaynak ve hedef cihazlar arasında veri akışını yönetir ve uygulama katmanı ile ağ katmanı arasındaki arabirim sağlar. Bu katman, verilerin güvenilir ve doğru bir şekilde iletilmesini sağlar ve veri akışını kontrol eder. Taşıma Katmanı, ağ üzerindeki uygulamalar arasında iletişimi düzenler ve uygulama verilerinin bütünlüğünü korur.

Taşıma Katmanı'nın temel görevleri şunlardır:

1. **Güvenilir Veri İletimi:** Taşıma Katmanı, verilerin güvenilir bir şekilde iletilmesini sağlamak için hata kontrolü ve akış kontrolü mekanizmalarını kullanır. Veri paketlerinde oluşabilecek hatalar tespit edilir ve düzeltilir. Veri akışı sırasında veri kaybı, çift gönderim veya düzensiz veri akışı gibi durumlar önlenir.

2. **Akış Kontrolü:** Taşıma Katmanı, veri akışının hızını ve miktarını düzenler. Alıcı cihazın, veri gönderen cihazdan daha yavaş veya daha hızlı çalışması durumunda, taşıma katmanı veri akışını ayarlar ve veri paketlerinin uygun bir hızda gönderilmesini sağlar. Bu, veri kaybını ve ağdaki trafik tıkanıklığını önler.

3. **Bölme ve Birleştirme (Segmentation and Reassembly):** Uygulama katmanından gelen veriler, ağdaki veri paketlerine bölünür (segmentation). Alıcı cihazda veriler birleştirilir (reassembly) ve orijinal veri elde edilir. Bu işlem, ağdaki veri paketlerinin boyutlarına uygun şekilde veri akışını yönetir.

4. **Port Yönetimi ve Bağlantı Kurma:** Taşıma Katmanı, uygulamalar arasında veri akışının yönetimi için port numaralarını kullanır. Kaynak ve hedef uygulamalar, port numaraları ile belirlenir. Bağlantı kurma ve bağlantı sonlandırma işlemleri de Taşıma Katmanı tarafından yönetilir.

5. **Akış Yönetimi (Flow Control):** Taşıma Katmanı, ağ üzerindeki veri trafiğini düzenleyerek yüksek veri akışlarından kaynaklanan ağ trafiği tıkanıklıklarını önler. Akış yönetimi, ağdaki cihazların veri alışverişi hızını uygun şekilde düzenler ve ağdaki kapasitenin verimli kullanılmasını sağlar.

Taşıma Katmanı, TCP (Transmission Control Protocol) ve UDP (User Datagram Protocol) gibi protokollerle uygulanır. TCP, güvenilir veri iletimini sağlayarak veri akışını akış kontrolü ve hata kontrolü ile düzenler. UDP ise daha az güvenilir ancak daha hızlı bir iletişim sunar ve akış kontrolü veya hata kontrolü mekanizmaları sağlamaz.

Taşıma Katmanı, ağ üzerindeki uygulamalar arasında güvenli, düzenli ve etkili veri iletimini sağlayarak internet ve diğer ağlar üzerinde uygulamaların doğru çalışmasına olanak tanır.
