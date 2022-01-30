## [1] Imperative Programming ve Declarative Programming kavramlarını kısaca açıklayıp farklarını belirtiniz.

Imperative Programming
- Ardışık sırada çalışan bir dizi talimat yazdığınız bir programlama paradigmasıdır.

Declaretive Programming  
- Ne yapılacağını içeren, nasıl yapılacağınının mantığını pek de içermeyen paradigmadır.

Farklar:
- İmperative yöntemde işlemi gerçeklemek için gereken tüm emirler verilerek detaylı bir şekilde gerçekleştirilir.
- Declarative yöntemde işlemin gerçekleştirilmesi için çağrilan metot aslinda işlemi gerçekleştirecek metotları çalıştırır. Bu şekilde işlemler soyutlanmış olur.

## [2] Veri tabanlarının sorgu optimizasyonlarında index oluşturmanın avantajı nedir ? Sık index kullanmak bir probleme yol açar mı?

Veritabanlarında indexleme sayesinde veri düzenlemesi belli bir sıraya göre yapılır bu şekilde yeni bir sorgu oluşturulduğunda database daha optimize çalışır. Database'deki veri büyükse bu şekilde sorgu süreleri kısaltılmış olur.

## [3] İlişkisel veritabanları için normalizasyon kavramı neyi ifade etmektedir ? İlk 3 normal formu örnek üzerinden açıklayınız.

Normalizasyon, veritabanındaki verileri düzenleme tekniğidir. Veri fazlalığını (tekrar), Ekleme, Güncelleme ve Silme Anomalileri gibi istenmeyen özellikleri ortadan kaldırmak için tabloları ayrıştırmanın sistematik bir yaklaşımıdır. Verileri tablo haline getiren, yinelenen verileri ilişki tablolarından kaldıran çok adımlı bir işlemdir.

## [4] ORM kütüphaneleri kullanmak her zaman avantajlı mıdır ? ORM kütüphanelerinin ne gibi dezavantajları olabilir ?

Avantajları
- Veritabanından bağımsız
- SQL sorguları yazmaya gerek yok
- Tablolar arasındaki bağımlılıklarla ilgilenir ve sorguları birleştirir
- İşlemlerin commit edilmesini ve geri alınmasını sağlar
- Veritabanı bağlantı havuzunu korur
- Bakımı kolaydır

Dezavantajları 
- ORM kullanımıyla ilgili bazı ek masraflar olacaktır
- ORM sayesinde geliştiricilerin işi kolaylaşır. Bu sayede SQL ve veritabanı işlerini öğrenmeyi atlayabilirler.

## [5] Domain Specific Language (DSL) kavramını açıklayınız.

Domain Specific Language belirli bir sorun sınıfı için optimize edilmiş daha yüksek bir soyutlama düzeyine sahip bir programlama dilidir. Bir DSL, alan veya etki alanındaki kavramları ve kuralları kullanır.

## [6] Long lived transaction kavramı hangi tip transactionları ifade etmektedir ? Dezavantajları var mıdır ? Varsa nelerdir ?

Birden çok veritabanı işlemini kapsayan işlemdir. Bir işlemin Long lived transaction olması için iş mantığı gereği tek bir veritabanı işlemini geçmelidir.

## [7] Thread Pool nedir ? Nerelerde kullanılır ?

Mevcut görevleri yürütmek için önceden oluşturulmuş thread'leri yeniden kullanır. Bu şekilde thread cycle overhead ve resource trashing'e çözüm sunar.

## [8] Scalability nedir ? Horizontal ve Vertical Scalability kavramlarını açıklayınız.

Sistemin yük altındayken çalışma kapasitesi Sistemin Scalability'sidir. Sistemin çalışmayı devam ettirebilmesi için kaynaklarının arttırılması gerekir. Artırma işlemi Horizontal ve Vertical olarak düzenlenebilir.

Horizontal Scalability
- Uygulamanın daha fazla makinede çalıştırılması horizontal scalability'dir.

Vertical Scalability
- Uygulamanın kullandığı makinelere teknik özellik bakımından kaynak artımı(ram, cpu, v.b.) vertical scalability'dir.

## [9] Data replication ve sharding nedir ? Aralarında nasıl bir fark bulunmaktadır ?

Data Replication
- Birincil sunucu düğümü, verileri ikincil sunucu düğümlerine kopyalar. Bu, birincil sunucunun arızalanması durumunda veri kullanılabilirliğini artırmaya ve yedek görevi görmeye yardımcı olabilir.

Sharding
- Shard Key'i kullanarak sunucular arasında yatay ölçeklendirmeyi yönetir. Bu replica kümeleri, tüm verileri kullanmak için birlikte çalışır.

