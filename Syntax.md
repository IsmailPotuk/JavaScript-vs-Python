# Python and JavaScript Syntax (Sözdizimi)

Değişkenler 

JavaScript Değişkenleri Ve Python Değişkenleri

JavaScriptte değişkenler tanımlanırken değişken oldukları beraberinde belirtilir, Python dilinde ise değişkenler direkt atanır. Değişkenler herhangi bir veri içeren "isimlendirilmiş hafıza" olarak adlandırılırlar.

JavaScript dilinde değişkenler "let" kelimesiyle üretilir. 

let mesaj;

mesaj = 'Merhaba'

Fakat Python dilinde direkt;

mesaj = 'Merhaba'

Python dilinde değişkenler için bir tür belirtme zorunluluğu yoktur, değişkenin türü yeni atalamarla değiştirilebilinir.

x = 4        # x değişkeni sayı (int) türündedir
x = "Sally"  # x şimdi metin (string) türüne dönüştü.  {Bu arada, "" ile '' arasında herhangi bir fark yoktur}

JavaScript dilinde SABİT (değişmeyen) değer tanımlamak için "let" yerine "const" kullanırız. 

Bu değişkenler "+" işaretiyle birbirlerine bağlanabilinir ve beraber işleme alınabilinir.

Pythonda bir metin ile değişkeni birleştirirken artı (+) işerati kullanılabilinir

Py
x = "selam"
print("py" + x)

py selam

Fakat sayı içeren bir değişkeni "+" ile birleştiremeyiz.

x = 5
y = "selam"
print (x + y)

BU ÇIKTIDA HATA OLACAKTIR -- bu sorunun çözümü 5 yerine "5" yazmak olacaktır. (5 selam)

Genel ve Yerel Değişkenler

Yerel değişkenler sadece tanımlandıkları kod bloğunda tanımlıdırlar fakat genel (global) değişkenler ile kodlarımızın tamamında tanımlıdırlar.
aşağıdaki örnekte ise x bir global değişken olarak tanımlanabilinir.

x = "selam"

def myfunc():
  print("selam" + x)

myfunc()

Eğer bir fonksiyonun içinde global değişkenle aynı isimde bir değişken tanımlanırsa bu sadece o fonksiyon için geçerlidir, dışarıda geçerli değildir.

Sadece fonskiyon içinde tanımlanıp, global yapılma teknikleride vardır.

def myfunc():
  global x
  x = "selam"

myfunc()

print("py" + x)

Çıktı: py selam












