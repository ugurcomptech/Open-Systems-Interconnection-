## Datalink Katman (Data Link Layer)

Datalink katmanı, fiziksel katmanın üzerinde bulunur ve verilerin doğrudan komşu cihazlar arasında güvenli bir şekilde iletilmesini sağlar. Bu katman, verileri çerçeve (frame) olarak adlandırılan küçük parçalara böler ve hata kontrolü yaparak doğru iletimini sağlar. Datalink katmanı, ağdaki iki komşu cihaz arasındaki doğrudan iletişimi sağlayarak ağdaki düğümler arasındaki veri alışverişini yönetir.

Datalink katmanının temel görevleri şunlardır:

1. **Çerçeveleme (Framing):** Veriler, datalink katmanında çerçevelere bölünür. Çerçeveler, verinin başlangıcını ve sonunu belirleyen baytlar içerir. Bu sayede alıcı cihaz, çerçevelerin başlangıcını ve sonunu tanıyarak veriyi düzgün bir şekilde alabilir.

2. **Hata Kontrolü (Error Checking):** Datalink katmanı, çerçevelerde oluşabilecek hataları tespit etmek ve düzeltmek için hata kontrol mekanizmalarını kullanır. Bu sayede veri iletimi sırasında oluşabilecek hatalar tespit edilir ve çerçeve yeniden gönderilir, böylece veri bütünlüğü sağlanır.

3. **Akış Kontrolü (Flow Control):** Veri alışverişi sırasında hız uyumsuzlukları ve veri birikimini önlemek için akış kontrolü mekanizmaları kullanılır. Alıcı cihaz, veriyi işlemeye hazır olduğunda göndericiye sinyal vererek veri akışını düzenler.

4. **Erişim Kontrolü (Access Control):** Datalink katmanı, ortak bir fiziksel ortamı (örn. Ethernet) paylaşan cihazlar arasında erişim kontrolünü sağlar. Ortak ortam üzerinde çakışan veri iletimini önlemek için bu mekanizmalar kullanılır. Örneğin, CSMA/CD (Carrier Sense Multiple Access with Collision Detection) Ethernet'te kullanılan bir erişim kontrol yöntemidir.

Datalink katmanı, genellikle iki alt katmana ayrılır:

- **LLC (Logical Link Control):** Mantıksal Bağlantı Kontrolü, ağ katmanı ile datalink katmanı arasında arabirim sağlar. LLC, veri iletimini düzenler ve hata kontrolü yapar.

- **MAC (Media Access Control):** Ortam Erişim Kontrolü, ağ arabirimini yönetir ve cihazlara benzersiz bir kimlik olan MAC adresi atar. MAC adresi, ağdaki cihazları ayırt etmek için kullanılır.

Datalink katmanı, ağdaki düğümler arasındaki doğrudan veri iletimini sağlayarak veri iletiminin düzenlenmesini ve güvenliğini sağlar. Bu katman, verilerin ağ üzerinde doğru ve güvenilir bir şekilde taşınmasını mümkün kılar.
