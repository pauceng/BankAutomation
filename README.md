## Banka Otomasyonu
> Yapılacak İşlemler:

**1. Yeni Kullanıcı Ekleme-Silme;**
	Banka işlemlerini yapacak kullanıcıların ekleme, silme ve güncelleme işlemleri yapılacaktır. Aynı kullanıcı adı başka kullanıcılar tarafından kullanılamayacaktır.
 **2.Hesap Açtırma;** 
 - Eğer müşterinin bankada hesabı yoksa Müşteriler tablosundaki verileri eksiksiz (boşluk bırakmadan)doldurulması gerekiyor. Müşterinin bilgilerinin güncellenebilmesi de gerekmektedir.
 - Bir müşterinin birden fazla hesabı olabilir.
 - Her hesabı için ayrı ayrı hesap numarası verilmesi gerekir. Aynı hesap numarası birden fazla müşteriye verilmemelidir. Hesap numaraları için otomatik artırım yapabilirsiniz.

**3. Para Çekme;** 
Müşteri, para çekecekse ilgili bilgiler girilip çekilen tutar kadar bakiyesinden bakiyesi yetmiyorsa ek hesabını kullanarak para çekme işlemi gerçekleşecektir. Günlük maksimum para çekme limiti 750 tl dir. Daha fazla para çekilmek istendiği takdirde işlem gerçekleşmeyecektir.

**4. Para Yatırma;**
Müşteri, para yatıracaksa ilgili bilgiler girilip yatırılan tutar kadar bakiyesi artacaktır.

**5. Hesaba Havale;**
Müşteri, havale yapacaksa; havale yapacağı kişinin Hesaplar tablosunda hesabının olması
gerekmektedir. Ardından havale tutarı kadar miktar kendi hesabının bakiyesinden eksilecek,
gönderdiği kişinin bakiyesi artacaktır.

**6. Banka Gelir-Gider Raporu;**
İstenen gün için bankanın gelir-giderleri(bankadan giden, gelen ve bankada bulunan toplam para
miktarı vb.) hesaplanıp görüntülenecektir.

**7. Hesap özeti;**
Seçilen bir hesap için belirtilen tarih aralığında hesap özeti görüntülenecektir. Çekilen, yatırılan,
havale yapılmışsa kime yapıldığı ve miktarı, başka bir hesaptan havale para geldiyse kimden geldiği
ve miktarı gibi bilgiler ve bu işlemlerin tarihleri görüntülenmelidir.

**8. Hesap Kapama;**
İstenilen hesap kapatılabilecektir. Kapama işlemi için hesap bakiyesi 0 olması gerekmektedir.

### Ekran Alıntıları

#### Giriş Paneli

![](/img/giris.gif)

#### Kullanıcı Paneli

![](/img/kullanici.gif)

#### Müşteri Paneli

![](/img/musteri.gif) 