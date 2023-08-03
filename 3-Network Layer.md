## Ağ Katmanı (Network Layer)

Ağ Katmanı (Network Layer), verilerin kaynak ve hedef cihazlar arasında nasıl iletilmesi gerektiğini belirler ve yönlendirme işlemlerini gerçekleştirir. Bu katman, veri paketlerinin farklı ağlara yönlendirilmesini ve hedef cihazlara ulaştırılmasını sağlar. Aynı zamanda, birden fazla ağ üzerinden iletişimi mümkün kılar ve ağların birbirleriyle haberleşmesini sağlayan önemli bir rol üstlenir.

Ağ Katmanı'nın temel görevleri şunlardır:

1. **Yönlendirme (Routing):** Ağ Katmanı, veri paketlerinin kaynak ve hedef cihazlar arasında en uygun yolu takip ederek iletilmesini sağlar. Birden fazla ağa bağlı cihazlar arasında veri iletimi için en iyi rota seçilir. Yönlendirme tabloları kullanılarak bu işlem gerçekleştirilir.

2. **Paketleme (Packet Encapsulation):** Ağ Katmanı, verileri alır ve paketlere (datagram) böler. Her paket, veriye ek olarak kaynak ve hedef adresleri, hata kontrol bilgileri ve diğer yönlendirme bilgilerini içerir. Bu paketleme işlemi, verilerin katmanlar arasında geçişini sağlar.

3. **Adresleme (Addressing):** Ağ Katmanı, her cihaza benzersiz bir IP (Internet Protocol) adresi atar. Bu adresler, cihazların ağ üzerinde tanınmasını sağlar ve veri paketlerinin doğru hedeflere ulaşmasını mümkün kılar. IPv4 ve IPv6 gibi IP adresleme yöntemleri bu katmanda kullanılır.

4. **Fragmentasyon ve Birleştirme (Fragmentation and Reassembly):** Veri paketleri, ağ üzerinde taşınırken farklı ağlarda değişen maksimum veri boyutlarına uygun hale getirilir. Eğer bir ağdaki maksimum veri boyutu, gönderilecek veri boyutundan küçükse, veri paketleri küçük parçalara bölünür (fragmentasyon). Alıcı cihazda paketler tekrar birleştirilir (birleştirme) ve orijinal veri elde edilir.

5. **Hata Tespiti ve Düzeltme:** Ağ Katmanı, veri paketlerinin iletimi sırasında oluşabilecek hataları tespit etmek için hata kontrol mekanizmalarını kullanır. Hatalı veri paketleri, yeniden gönderme veya düzeltilmiş haliyle alıcılara gönderme işlemleri gerçekleştirilir.

Ağ Katmanı, verilerin kaynak ve hedef cihazlar arasında güvenli bir şekilde yönlendirilmesini ve ağlar arasında iletişimi sağlayarak internet ve geniş alan ağları gibi büyük ağların çalışmasını mümkün kılar. IP tabanlı iletişim, Ağ Katmanı'nın temelinde yatan anahtar prensiptir ve modern ağların işleyişini temel olarak bu katman belirler.
