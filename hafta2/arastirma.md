[1] - 
 Salta, Weld, Guice, Play framework, Glassfish HK2, Dagger.
[2] - 
@SpringBootApplication anotasyonunun kapsadığı anatasyonlara örnek olarak @Configuration, @ComponentScan, @EnableAutoConfiguration anotasyonları gösterilebilir.

@Configuration
Bu anotasyon, bir class'ı Java tabanlı configuration için bir Configuration class olarak işaretler.

@ComponentScan
Bu anotasyon, oluşturduğunuz web controller class'ları ve diğer bileşenlerin otomatik olarak bulunmasını ve Spring'in Uygulama Bağlamında bean olarak kaydedilmesi için öğe taramayı etkinleştirir. Yazılan tüm @Controller class'lar bu anotasyon tarafından keşfedilir.

@EnableAutoConfiguration
Bu anotasyon, birçok şeyi otomatik olarak yapılandırabilen Spring Boot'un auto-configuration özelliğini etkinleştirir.

[3]

@Primary - @Component anotosyonlu class'larda ve @Bean anotasyonlu metodlarda kullanılmaya uygundur. Birden fazla aynı türden Bean olması durumunda @Primary anotasyonlu olan seçilir.

@Qualifier - Dependency Injection yaparken birden fazla uygun aday olması durumunda tercih edilecek adayı belirlemek için kullanılır. @Qualifier anotasyonu varsa @Primary anotasyonu yok sayılır.

[4] - 
framework'ler tarafından kullanılan ve framework'ü kullanan geliştiricinin, esnekliğini kaybetmeden vermesi gereken kararların sayısını azaltmaya çalışan yazılım tasarım paradigmasıdır.

[5] - 
Aspect Oriented Programming yazılımdaki karmaşıklığı azaltmayı ve modüleriteyi artırmayı hedefleyen yaklaşım biçimidir. Seperation of Cross Cutting Concerns fonksiyonel olmayan kodun yani kesişen ilgilerin ufak parçalara ayrılmasıdır.

[6] - 
Yazılımın esnek, yeniden kullanılabilir, sürdürülebilir ve anlaşılır olmasını sağlayan, kod tekrarını önleyen prensipler bütünüdür. 

Single responsibility - Bir sınıf yalnızca bir işi yapmaktan sorunludur.
Open closed principle - Davranışı değişmeden yeni özellikler kazanmaya açık olmalıdır.
Liskov substitution principle - Kodlardda değişiklik yapmadan alt sınıfları türedikleri sınıfların yerine kullanmaya olanak sağlamalıdır.
Interface segregation principle - Tek arayüze tüm sorumlulukları toplamak yerine birden fazla özelleştirilmiş arayüz oluşturulmalıdır.
Dependency inversion principle - sınıflar arası bağımlılıklar en az seviyede olmalıdır.

[7] - 
Swagger Api dökümantasyonunu el ile yazmaktan kurtarır ve güncel olarak üretilmesini sağlar.

[8] - 
Richardson Maturity Model Rest API’lerimizin hangi seviyede olgun olduğunu gösteren bir olgunluk seviyesidir. RMM 4 seviyeden oluşmaktadır. 0’dan başlar yukarı doğru çıktıkca daha etkin kullanıldığını ifade eder.

level 0(Swamp of POX) - Servisdeki sadece tek metod üzerinden POST olarak erişim sağlanılan seviyedir. Bu seviye transfer protokolü olarak da adlandırılır.
LEVEL 1(Resources) - Servisdeki URl bir metod üzerinden erişim sağlanan seviyedir.
level 2(HTTP verbs) - POST, PUT, GET, DELETE metotlarının çağrılabildiği seviyedir.
level 3(Hypermedia controls) - HATEOAS kullanılan seviyedir. Servis URl'nin istek gönderip cevaba göre tekrar URl'ye istek yapabildiği bir seviyedir.

[9]

URL (Uniform Resource Locator) - URL internet kullanarak erişişebilecek kaynakların konumunu ifade eder. URI’nın başlangıç kısmını URL olarak oluşturur. örnek https://developer.mozilla.org
URI (Uniform Resource Identifier) - kaynağa identifier ile işaret eden ve bu işaretleme için standart bir formata sahip karakter dizisidir. URL kapsamında tutulan alt tanımlardır. örnek http://ornekwebsitesi.com/logo.png
URN (Uniform Resource Name) - Bir kaynağı benzersiz ve kalıcı bir adla tanımlar, ancak bunu İnternet’te nasıl bulunacağının söylenmesi gerekmez. Belgeleri tanımlamakla sınırlı değildirler. örnek urn:isbn:00000000000

[10] - 
Bir metodun başarıyla çalışması sonrası tekrar çağrılması durumunda yeni bir değişiklik olmadan çalışmasıdır.
Idempotent HTTP metotlar - GET, HEAD, OPTIONS, TRACE.

[11] - 
RFC internetle ilgili standartların ve teknik yayınların resmi bir kural olmadığını belirtir. HTTP'nin amacı, kuralları, method'ları, status code'larını içerir. 