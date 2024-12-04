# ÇOKLU VERİ ELEMANLARI
Çoklu veri elemanları, tek bir değişkende birden fazla veriyi depolayabildiğimiz yapıya denir. Python'da "çoklu veri elemanları" terimi, birden fazla veriyi tek bir yapıda saklamaya yarayan veri türlerini ifade eder. Python, birden fazla veri elemanını bir arada tutabilen ve üzerinde işlem yapabilen çeşitli veri yapıları sunar. Bunlar genellikle koleksiyon (collection) veri türleri olarak adlandırılır.

Python'da çoklu veri elemanları kullanabileceğiniz başlıca veri yapıları şunlardır:
1) Listeler
2) Diziler
3) Demetler
4) Sözlükler
   
# LİSTELER
Çoklu veri tiplerini tutmamızı sağlayan dizilerdir. Adından da anlaşılaca ğı üzere içerisinde liste şeklinde birden fazla eleman bulundurmaktadır.

Peki, Python'da liste nasıl oluşturulur? Bunun hakkında bilgi sahibi olalım.

Öncelikle listenin ismini girmeliyiz ve liste içerisine veri atama işlemi gerçekleştirebilmek için eşittir sembolünü koymalıyız. Evet, şimdi buradan sonra en önemli kısım; liste elemanlarını bizler köşeli parantez içerisinde yazmalıyız ve elemanlan birbirinden ayırmak için ise virgül sembolunü kullanmalıyız. Eğer liste içerisinde "string" bir ifade varsa onu tırnak içerisinde yazmalıyız. Bir örnek üzerinden inceleyelim:

isimler=["Ali", "Ayse", "Mehmet", "Fatma"]

print(isimler)

<a href="https://github.com/ebrarrkaya/404/blob/a5b9103843335323bbbfe53eca38b9ee442c793f/z.png">ÇIKTISI İÇİN TIKLAYINIZ</a>

Liste içerisindeki tüm elemanların birer indeks numarası bulunmaktadır. Baştan sona doğru "0, 1, 2," şeklinde numaralandırılmaktadır. Bu durumda: 'Ali' ifadesinin indeks numarası O'a. 'Ayse' ifadesinin indeks numarası 1'e, 'Mehmet' ifadesinin indeks numarasi 2'ye, 'Fatma' ifadesinin indeks numarası ise 3'e denk gelmektedir. Şimdi içerisinde farklı tiplerde veri barındıran bir liste oluşturup içerisindeki verilere ulaşalım.

isimler=["Ali","Ayse", "Mehmet",1.2.0]

print(isimler[3])

<a href="https://github.com/ebrarrkaya/404/blob/122f995dc356646356b8b225372338f8b4d89cb2/A.png">ÇIKTISI İÇİN TIKLAYINIZ</a>


Görüldüğü üzere listemizin içerisine farklı veri tipinde elemanlar atadık ve her birinin birer indeks numarası bulunmaktadır. Liste içerisinden 1 elemanına ulaşmak için o elemanın indeks numarasını (3) girdik.

[LISTEYE ELEMAN EKLEME İŞLEMİ](https://github.com/ebrarrkaya/404/blob/ed84c8236510c0e679fbdbe1f6c3725cbfd444dd/ekleme.md)

[LISTE İÇERİSİNDEKİ ELEMANI ÇIKARTMA](https://github.com/ebrarrkaya/404/blob/ed84c8236510c0e679fbdbe1f6c3725cbfd444dd/C%C4%B0KARTMA.md)

[LISTE İÇERİSİNDEKİ ELEMANI DEĞİŞTİRME](https://github.com/ebrarrkaya/404/blob/08a9ec487e4f08c700f312890da6ccf6e113fd1d/eleman%20de%C4%9Fi%C5%9Ftirme.md)







