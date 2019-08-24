2018/2019 Yılı PAÜ Bilgisayar Mühendisliği bölümü

Nesneye Yönelik Programlama Proje Ödevi

w/ <a href=https://github.com/engincankizilyar>Engincan Kızılyar</a>


## LoginForm
<img src=readme-img/LoginForm.png width=400><br>
Programımızın ilk açılışında bizi karşılayan ekran. Database’de halihazırda önceden tanımlanmış yetkili kullanıcı bilgileri ile giriş yapılabilen bir ekran aynı zamanda sağ üstteki “Info Button” tıklandığında developer isimlerini “MessageBox” şeklinde gösteriyor.<br>

## MenuForm
<img src=readme-img/MenuForm.png width=700><br>
Login ekranından sonra yukarıda gördüğünüz gibi bir menü bizi karşılıyor. Müşteri Kayıt, Müşteri Güncelle, Müşteri Çıkış, Oda Ekle, Oda Güncelle gibi işlemleri yapabileceğimiz bu ekran sade ve kullanıcı dostu bir arayüz olmasıyla beraber kolay bir kullanış sunuyor. Aynı zamanda menünün üst kısmında yer alan “Hoşgeldiniz” kısmında ise bir önceki “Login” ekranında giriş yapan kullanıcının ismi yazıyor.<br>

## MusteriKayit
<img src=readme-img/MusteriKayit.png width=700><br>
Müşterinin kaydının yapıldığı ekran. Üst taraftaki menüde müşteri bilgileri ve müşterinin kalacağı oda  ve tarih bilgileri girildikten sonra “Ekle” butonuyla beraber alt taraftaki “Müşteri Liste” de anlık olarak eklenilen müşteri görülecektir. Oda No yazan “ComboBox” Otel’de bulunan boş odaları listelemektedir yani böylece aynı odayı birden fazla müşteriye verme gibi bir sorun ortadan kalkacaktır. Aynı zamanda 0-12 yaş arası çocuk var ise girilecek, eğer yoksa yetişkin olarak kabul edilecektir.<br>

## MusteriGuncelle
<img src=readme-img/MusteriGuncelle.png width=700><br>
Otelde bulunan tüm müşterileri listeleyen bir tablo ve altında da yukarıdaki tablonun “Clicked Event” i ile beraber bilgileri gösteren textbox’lar bulunmaktadır. Gerekli işlemler yapıldıktan sonra “Güncelle” butonu ile beraber işlem tamamlanıp, tablo anlık olarak güncellenecektir.<br>

## MusteriCikis
<img src=readme-img/MusteriCikis.png width=700><br>
Müşteriyi silme ekranında yine tablonun “Clicked Event” i ile beraber bilgiler listelenir ve eğer ki 0-12 yaş arası çocuk 0’dan büyük ise odanın toplam fiyatı üzerinden %20’lik bir indirim uygulanır ve “label” a yazdırılır.<br>

## OdaEkle
<img src=readme-img/OdaEkle.png width=700><br>
Üst tarafta eklenecek odanın gerekli bilgileri girildikten sonra “Ekle” butonuyla beraber alttaki tabloda anlık olarak gösterilir.<br>

## OdaGuncelle
<img src=readme-img/OdaGuncelle.png width=700><br>
“MusteriGuncelle” ile aynı özellikleri taşıyan oda bilgilerini güncelleyeceğimiz ekran.
