## [1] Regression test nedir ? Kısaca açıklayınız.

Gerçeklenen bir program veya kod değişikliğinin mevcut özellikleri olumsuz etkilemediğini doğrulamak için yapılan bir tür yazılım testi olarak tanımlanır. Regresyon Testi, mevcut işlevlerin düzgün çalışmasını sağlamak için yeniden yürütülen, halihazırda yürütülmüş test senaryolarının tam veya kısmi seçimidir.

## [2] A/B test nedir ? Kısaca açıklayınız.

A/B testi, hangisinin daha iyi performans gösterdiğini belirlemek için bir web sayfasının veya uygulamanın iki sürümünü birbiriyle karşılaştırma yöntemidir.

## [3] Black box / white box test kavramlarını açıklayınız.

Black box test 
- Spesifikasyonlara dayalı olarak bir uygulamanın işlevselliğini inceleyen bir yazılım testi yöntemidir. Spesifikasyon tabanlı test olarak da bilinir. Bağımsız Test Ekibi genellikle bu tür testleri yazılım testi yaşam döngüsü sırasında gerçekleştirir.

White box test  
- girdi-çıktı akışını doğrulamak tasarım, kullanılabilirlik ve güvenliği geliştirmek için yazılımın iç yapısının, tasarımının ve kodlamasının test edildiği yazılım test tekniğidir.


## [4] Mutation test nedir ? Kısaca açıklayınız.

Bir yazılım test paketinin değişiklikleri algılayabilmesini sağlamak için testçilerin bir uygulamanın kaynak kodunun belirli bileşenlerini değiştirdiği **White Box** test şeklidir. Yazılımda yapılan değişikliklerin programda hatalara yol açması amaçlanır.

## [5] Behavior Driven Development (BDD) nedir, neyi amaçlamaktadır ?

Behavioral Driven Development (BDD), TDD (Test Driven Development) gelişen bir yazılım geliştirme yaklaşımıdır. Teknoloji ve teknoloji dışı ekipler, paydaşlar arasındaki iletişimi geliştiren ortak bir dilde yazılmasıyla farklılık gösterir. Her iki geliştirme yaklaşımında da testler kodun önüne yazılır, ancak BDD'de testler daha kullanıcı odaklı ve sistemin davranışına dayalıdır.	

## [6] Agile test quadrant nedir ? Quadrant’ların kapsamını kısaca açıklayınız.

Agile Test Çeyrekleri, farklı QA testlerini anlamak için görsel bir araçtır. İş ve teknolojiye yönelik testler ile ürünü programlamayı veya "eleştirmeyi" destekleyenler arasında ayrım yapılır. Test türleri, bir grid üzerinde bu dört kategoriye ayrılır.

![Ekran görüntüsü 2022-01-30 235052](https://user-images.githubusercontent.com/53883971/151717332-0ce6852b-5212-4998-892d-1072d74ba0d3.png)

<br />
Q1
- Uygulamanızın geliştirilmesi boyunca birim ve bileşen testleri yapılır. Geliştiricilerinize, genellikle tekrarlanan, otomatikleştirilmiş süreçler aracılığıyla sürekli olarak kodlarının kalitesi hakkında geri bildirim sağlarlar.

<br />

Q2
- Manüel ve otomatik testlerin bir kombinasyonuyla, bu 'işe yönelik' testler daha müşteri odaklıdır, ancak uygulama oluşturmanızı da destekler. Bunlar, ürünün yapması gerekeni yapmasını sağlayan fonksiyonel testleri içerir.

<br />

Q3
- User Acceptance Test'leri (UAT), kullanılabilirlik ve keşif testleri bu çeyreğe aittir. Bunlar, deneyimli QA mühendisleri tarafından yapılan manuel testleri ve son kullanıcı testlerini içerir. Buradaki amacınız, geri bildirim almak ve ürünün kalitesini artırmak, tasarlanan amaca uygun olmasını sağlamaktır.

<br />

Q4
- Bunlar, yük testi ve yazılım uygulamanızın veri güvenliğini kontrol etme gibi teknolojiye yönelik performans testleridir. Bu tür testleri otomatikleştirmek için JMeter ile birlikte kullanılan Selenium gibi birçok araç vardır.