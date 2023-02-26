# Python and JavaScript Data Types (Veri Türleri)

Python veJavaScript'te toplamda 8 farklı veri türü vardır.

Bunlar: 

JS İçin:
String
Number
Bigint
Boolean
Undefined
Null
Symbol
Object


Python İçin:
Text
Numeric
Sequence
Mapping
Set
Boolean
Binary
None

Öncelikle JS için olan veri tiplerine bakalım:

Number-Sayı: Sayınar toplama, çıkarma, çarpma ve bölme işlemine girebilirler. Infinity ve NaN gibi depğerlerde vardır. Infinity sonsuzluğu belirtirken NaN ise matematiksel bir problemi söyler.

Sting - Karakter: JS'de karakter dizileri çift tırnak içerisine alınmalıdır. Çift tırnak ile tek tırnak arasında fark yoktur fakat ters tırnak konusundaki durum farklıdır.
Ters tırnak ise “genişletilmiş fonksiyonlu” tırnaktır. Bunu kullanarak karakter dizisi içerisine ${...} gibi başka bir dizi yerleştirebiliriz
let isim = "Ahmet";

// değişken gömme
alert( `Hello, ${isim}!` ); // Merhaba Ahmet!

// ifade gömme
alert( `sonuç : ${1 + 2}` ); //sonuç :  3


Boolean Tipi (Doğru/Yanlış):

Boolean tipi true ve false olmak suretiyle sadece iki değer tutabilir.

let buyuk = 4 > 1;

alert( buyuk ); // true (cevap görüldüğü gibi "doğru" çıkacaktır.)

Null Veri Tipi:

"olmayan", "boş" veya "bilinmeyen değer" anlamına gelen özel bir değerdir

Undefinded Değeri:

Eğer bir değişken tanımlanmış fakat deger atanmamışsa tam olarak bu değeri alır.
let x;

alert(x); // "undefined" çıktısı verir.


typeof Operatörü:

typeof argüman tipini bildirir.typeof undefined // "undefined"

typeof 0 // "number"

typeof true // "boolean"

typeof "foo" // "string"

typeof Symbol("id") // "symbol"


PYTHON İÇİN:

Veri Türünü almak için: type() işlevini kullanabilirsiz.

x = 5
print(type(x))

işin güzel yanı, aynı durumlar olduğu gibi Python için geçerlidir.































