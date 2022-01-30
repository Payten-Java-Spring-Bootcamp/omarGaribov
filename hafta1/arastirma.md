[1] - 
Pass by value yaklaşımına göre parametreler metotlara gönderilirken parametrenin 
değerini tutan değişkenin adresi yerine direk değerin kendi gönderilmiş olur. Bu 
şekilde metot içerisinde yapılan işlemler orijinal değişkenin bir kopyası üzerinde 
yapılmış olur ve orijinal değişken bu işlemlerden etkilenmez. Java’da primitive 
type’lar pass by value ile gönderilir. Pass by referance yaklaşımına göre ise metoda
hafızada değişkenin değerini saklayan bloğun adresi gönderilir. Java’da objeler 
otomatik olarak pass by referance ile gönderilir.

[2] - 
Nesne bir kere Immutable class’lar değişmez olur. Immutable class’lardan üretilen
nesneler ilk değerlerini constructor metotlarla alır ve sonrasında değişime 
uğramazlar. Java’da immutable class oluşturmak için değişkenler final olarak 
tanımlanmalı aynı zamanda private olmalı, değişkenlerin setter metotları olmamalı, 
değişkenlere ilk değerler constructor metotlarla atanmalı ve class’ın kendisi de final 
olarak tanımlanmalıdır.

[3] - 
Kullanıcı library’leri nasıl ve nerede kullanacağına kendi karar verir ve kodlar hazırdır. 
Yani kullancici library’yi istediği gibi kullanmakta özgürdür. Framework ise bir 
uygulama çatısıdır yani kullanıcı uygulamayı bu çatıya uygun olacak şekilde 
geliştirmelidir. Kodları kullanıcı yazar. Library’ler Framework’ler içerisinde 
kullanılabilir.

[4] - 
Bellek yönetimi işlemlerinin c/c++ gibi dillerdeki gibi kullanıcının kontrolüne 
bırakılması yerine otomatik olarak gerçekleştirilmesini sağlar. Bu sayede kullanıcı bir 
endişe duymadan yeni nesneler yaratır ve Garbage Collector kullanıcı yerine memory 
allocation ve deallocation işlemlerini gerçekleştirir.

[5] - 
Programın kullanılan hafızayla işi bittiği halde serbest bırakmadığında oluşan 
durumdur. Her ne kadar java’da garbage collector mevcut olsa da memory leak 
oluşması durumları oluşabilir. Örneğin statik alanların aşırı kullanılması potansiyel 
olarak bellek sızıntısına yol açabilir.

[6] - 
OpenJDK 6 ayda bir, OracleJDK 3 yılda bir.

[7] - 
Stack-Last in First out.
Stack ve Heap ram’in bölümleridir.Stack’e erişim daha hızlıdır. Stack’de değer tipleri, 
pointer ve adresler, Heap’de referans değerleri tutulur.

[8] - 
İkisi arasında teknik bir fark bulunmamaktadır. Performans bakımından oracle yanıt 
verme ve jvm performansı açısından daha iyidir.

[9] - 
Java 8 sürümü ile gelmiş özelliklerden biridir. İçerisinde sadece bir tane abstract 
metot barındırır. Lambda expression’ların kullanılabilmesi için tanımlanır.

[10] - 
Functions, Supplier, Predicate çok kullanılan functional interface’lere örnek verilebilir.