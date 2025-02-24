### Giriş

Test Güdümlü Geliştirme, kısaca TDD, modern yazılım geliştirme dünyasında _büyük_ bir öneme sahiptir. Bu kavramı, JavaScript alıştırmalarımızla birlikte Temel Bilgiler bölümünde çok önceden tanıtmıştık. Temel fikir, test edilen kodu yazmadan önce otomatik testler yazarak çalışmaya başlamaktır. Bu şekilde çalışmanın birçok faydası vardır ve bunların tamamı aşağıdaki kaynaklarda tartışılacaktır.

JavaScript’te birçok test çalıştırma sistemi mevcuttur: [Mocha](https://mochajs.org/), [Jasmine](https://jasmine.github.io/), [Tape](https://github.com/substack/tape) ve [Jest](https://jestjs.io/) bunlardan sadece birkaçıdır. Neyse ki, her birinin sözdizimi oldukça benzerdir. Hepsinin kendine özgü bazı özel özellikleri olsa da temel sözdizimi neredeyse aynıdır, bu yüzden hangisini kullandığınız pek fark etmez. Aslında, bu müfredat için hangi kütüphaneyi seçmenin oldukça zorlayıcı olduğunu söyleyebiliriz!  

Bu ders __Jest__ etrafında şekillenecek. Bu kararı vermemizin en büyük nedenleri, JavaScript testlerini açıklamak için bulduğumuz en iyi kaynaklardan birinin __Jest__ kullanması ve __Jest__'in harika bir dokümantasyona sahip olmasıdır. Sonuç olarak, test yazmak sözdiziminden çok __TDD__ felsefesi ile ilgilidir. En önemli konular, testleri __neden__ yazdığımız ve __neyi__ test ettiğimizdir, nasıl yazdığımızdan daha az önemlidir.

### Derse genel bakış

Bu bölüm, bu derste öğreneceğiniz konuların genel bir özetini içerir.

- TDD'nin temel kavramlarını açıklayın.  
- Jest ile çalışmaya başlayın.  
- Temel testler yazın.

### Ödev

<div class="lesson-content__panel" markdown="1">  
1. [Bu kısa makaleyi okuyun](https://web.archive.org/web/20211123190134/http://godswillokwara.com/index.php/2016/09/09/the-importance-of-test-driven-development/). Bu makale, TDD'nin temel sürecini ve faydalarını açıklar.  
2. JavaScript’te test yazma hakkında olan [bu video serisinin](https://www.youtube.com/playlist?list=PL0zVEGEvSaeF_zoW9o66wa_UCNE3a7BEr) en az ilk 3 videosunu izleyin. İlk video daha çok **neden** test yazmamız gerektiğini ele alırken, sonraki iki video sürecin detaylarına iner. Serideki diğer videolar da _kesinlikle_ faydalıdır, ancak ilk 3 video başlangıç için yeterlidir.  
3. Jest’in ana web sitesindeki [Başlangıç Kılavuzunu](https://jestjs.io/docs/getting-started) okuyun ve adımları takip edin. Yaklaşan test pratiği ve proje için yalnızca Jest'in nasıl kurulacağını öğrenmeniz yeterlidir.  
4. Jest’in ana web sitesinde bulunan [Matchers Kullanımı](https://jestjs.io/docs/using-matchers) dokümanını okuyun ve takip edin. Bu doküman, testlerinizde kullanabileceğiniz diğer bazı faydalı fonksiyonları göstermektedir.  
</div>

### Bilgi ölçme	

Bu bölüm, bu dersi kendi kendinize anlayıp anlamadığınızı kontrol etmeniz için sorular içermektedir. Bir soruyu yanıtlamakta zorlanıyorsanız, soruya tıklayın ve bağlantılı olduğu materyali gözden geçirin.

-  [TDD'nin yararları nelerdir?](https://web.archive.org/web/20211123190134/http://godswillokwara.com/index.php/2016/09/09/the-importance-of-test-driven-development/)
-  [Yaygın olan jest matcher'lar nelerdir?](https://jestjs.io/docs/using-matchers#common-matchers)

### Ek kaynaklar

Bu alanda içerikle alakalı faydalı linkler bulunmaktadır. Zorunlu değildir, ek olarak düşünülmelidir.

-  Görünüşe göre bu derste henüz ek kaynak yok. Müfredatımıza katkıda bulunarak bu bölümü genişletmemize yardımcı olun.
