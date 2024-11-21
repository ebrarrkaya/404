# İNDEKS KAVRAMI
Python'da indeks, bir koleksiyon veri yapısındaki (örneğin liste, demet, dize, vb.) bir öğenin konumunu belirtmek için kullanılan sayısal bir değerdir. Python'da koleksiyonlar sıralı (ordered) veri yapılarıdır, yani her öğenin bir sırası vardır ve bu sıra indeks ile temsil edilir.

Çoklu verideki her bir elemanın konumu indeks ile temsil edilir. İndeks, her daim 0'dan başlar ve toplam eleman sayısının 1 eksiğinde sonlanır. Yani çoklu verinin bulunduğu konumun indeksi 0'dır. Kullanımı, coklu_veri_degiskeni[indeks_numarasi] şeklindedir.

ÖRNEK:

liste=[1,2,3,4,5]

print(liste[2])

<a href="https://github.com/ebrarrkaya/404/blob/64fdfdfed244761e1979b585928026330945f200/e1.PNG">ÇIKTISI İÇİN TIKLAYINIZ</a>

Eğer bizler girdiğimiz metinsel ifadenin tek bir verisine değil de bir indeksinden başlayıp bir diğer indeksine kadar olan kısmını çıktı almak istersek, önce başlangıç indeksini girerek, arasına iki nokta üst üste sembolünü koyup, bitiş indeks numarasını girmeliyiz. Örnek üzerinden inceleyelim.

degisken="Bugun hava cok guzel"

print(degisken [6:10])

Burada 6. indekse denk gelen h ifadesinden başlayarak, 9. indeks olan a ifadesine kadar olan kısmı kapsayacak şekilde verimizi çıktı aldık. Burada belirttiğimiz son indeksteki veri gösterilmemektedir. Yani, 1 eksiği olan 9. indeks dahil edilmektedir

<a href="https://github.com/ebrarrkaya/404/blob/63664db7ea9ab4e83212f963d1864e0d29879b0d/E3.PNG">ÇIKTISI İÇİN TIKLAYINIZ</a>

Eğer başlangıç indeksini 0, indeks olarak almak istersek "0" indeksini yazmak yerine iki nokta sembolünü kullanmamız yeterli olacaktır. Ya da en son veriyi bitiş verisi olarak belirlemek istersek indeks numarası girmek yerine iki nokta üst üste sembolünü kullanabilmekteyiz. Örnek üzerinden inceleyelim.

degisken="Bugun hava cok guzel"

print(degisken[:10])

<a href="https://github.com/ebrarrkaya/404/blob/1188838db4b71f6299817118fbf2be22d27b90ec/e5.PNG">ÇIKTISI İÇİN TIKLAYINIZ</a>

Bir de bitiş noktasını metnin en son verisi olarak aldığımız bir örneği inceleyelim:

degisken="Bugun hava cok guzel"

print(degisken[6:])

<a href="https://github.com/ebrarrkaya/404/blob/d5e8413b0fc50954df6b1e8c403cb244a3fd4420/e4.PNG">ÇIKTISI İÇİN TIKLAYINIZ</a>
