# Fetch API İle Çalışmak 
`Fetch API`,kaynakları (ağ genelinde dahil)  getirilmesine yönelik basit bir arayüzdür.`Ajax` yerine alternatif olarak asenkron veri alıp ve veri göndermemizi sağlar.Promise tabanlı olduğu için async bir yapıdır.`Promise` ES6 ile gelen bir özelliktir.Callback fonksiyonlarının yerine kullanabiliyoruz.Fetch API'da promise yapısını kullanarak bizim Ajax'ın yerine kullanabileceğimiz bir yapı sunuyor.Ayrıca Fetch API  window objesi ile birlikte geliyor. Eğer window objesini konsolda yazdırırsak bu window objesinin altında fetch metodunu görebilirsiniz.

Fetch API ile yapabildiğimiz şey bir veri sunucudan geldikten sonra işlem yapabilmektir.Peki bu ne demektir? Diyelim ki bir yere gittiniz ve sipariş veriyorsunuz.Kasadaki kişi siparişi aldıktan sonra kasada beklersek bir sonraki kişinin siparişinin vermesini engelleriz.Belki de bir sonraki kişinin siparişi çok daha hızlı hazırlanabilirdi.Bu durumda şunu da unutmamak lazım bizne zaman sipariş ettiğimiz ürenleri gidip almak isteriz? Tabii ki siparişimiz hazırlandıktan sonra.Burda aslında yeni gelen kavramlardan bir tanesi olan Promise'i kullanırız.

## Fetch Interfaces

*`fetch()`,bu yöntem bir kaynak almak için kullanılır.

*`Headers`, response/request başlıklarını temsil ederek bunları sorgulamanıza ve sonuçlara bağlı olarak farklı eylemler gerçekleştirmenize olanak tanır.

*`Request` ,bir kaynak talebini temsil eder.

*`Response`,bir isteğe verilen yanıtı temsil eder.

## Temel Fetch Kullanımı 
Fetch API’ yi kullanmak için fetch metoduna istek yapacağımız url’ i parametre olarak vermek gerekiyor.
```
fetch(url)
```
fetch() metodundan sonra, metodun sonuna then() promise metodunu ekleriz:
``.then(function() {

})
```
