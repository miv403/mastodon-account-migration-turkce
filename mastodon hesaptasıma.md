# mastodon hesap nasıl taşınır?


### neleri taşıyabiliriz

- takipçiler
- takip edilenler
- engellenen kişiler
- susturulan hesaplar
- yer imleri

gönderilerinizi taşıyamazsınız ama hesabınızın arşivini isteyerek dışarı aktarabilirsiniz. indirdiğiniz tar.gz uzantılı arşiv dosyasının içinde outbox.csv adlı dosyada tüm iletilerinizi (tootlar ve doğrudan mesajlar) bulabilirsiniz. arşivinizi istemek aşağıda da gösterdiğim gibi dışa 

#### #1
taşımak istediğiniz sunucuda hesap açın.

#### #2
taşıyacağımız (eski) hesaba giriş yapıp tarayıcıdan ayarlar kısmına giriyoruz ve dışa aktar kısmından takip edilenler listemizi indiriyoruz. ileride lazım olacak. eğer engellenenler, susturulanlar gibi taşımak istediğiniz başka bir liste varsa onları da indirin.

![işaretli olan csv yazısına tıklayın ve takip edilenler listesini indirin](https://i.hizliresim.com/5ewv7sz.jpg)

> işaretli olan csv yazısına tıklayın ve takip edilenler listesini indirin.

indirdiğiniz dosyanın yerini lütfen kaybetmeyin. 

#### #3
ayarlar kısmından hesap seçeneğinin altındaki hesap ayarları sekmesine girin. aşağıda bulunan farklı bir hesaba taşı başlığını bulun. sonra "buradan yapılandırın" bağlantısına tıklayın.

![enter image description here](https://i.hizliresim.com/b417w8z.jpg)


![enter image description here](https://docs.joinmastodon.org/assets/account-redirect.jpg)

önceden açtığımız hesabı "kullaniciadi@alanadi" biçiminde ve mevcut parolanızı ilgili kutucuklara girin. sonra yönlendirmeyi ayarla düğmesine tıklayın.

#### #4

taşımak istediğiniz yeni hesabınıza giriş yapın ayarlar > hesap ayarları yolunu takip ederek aşağıdaki ekrana ulaşın. alt kısımdaki başka bir hesaptan taşıma başlığının altındaki hesap takma adı oluşturun kısmına tıklayın. 

![enter image description here](https://i.hizliresim.com/tthgb9s.jpg)

açılan yere taşındığınız (eski) hesabınızın adını kullaniciadi@alanadi biçimde girin ve takma ad oluşturun düğmesine tıklayın.
bu eski hesabınızın yeni hesabınıza yönlendirmesini geçerli kılacak. bir nevi bu hesaba yönlendirmeye izin vermiş oluyorsunuz.

![enter image description here](https://docs.joinmastodon.org/assets/account-aliases.jpg)

bundan sonra eski hesabınıza giriş yaptığınızda anasayfa yerine ayarlar kısmına yönlendirileceksiniz ve eski hesabınızın yeni hesabınıza yönlendirildiği ile ilgili bir bilgilendirme mesajı ile karşılaşacaksınız.

işlem yavaş sürebilir. eğer hesabınıza giriş yapmadan profilinize girdiğiniz de aşağıdaki gibi bir yönlendirme yazısı göremiyorsanız işlemleri tekrar etmeyi deneyebilir ya da biraz bekleyebilirsiniz.

![enter image description here](https://i.hizliresim.com/253tcdx.jpg)



#### #5

bu yaptıklarımız sadece takipçilerimizi aktardı. şimdi önceden indirdiğimiz takip edilenler listesini aktarmamız gerekiyor.

![enter image description here](https://i.hizliresim.com/hksi9su.jpg)

ayarlardan içe ve dışa aktar sekmesinin altındaki içe aktar kısmına girin ve takip edilenler listesi seçeneğini işaretleyin. gözat düğmesine basıp daha önce indirmiş olduğunuz .csv uzantılı (following_accounts.csv) dosyayı seçin. sonra yükle düğmesine basın.

eğer çok fazla takip ettiğiniz kişi varsa işlem biraz daha gecikmeli olabilir. nihayetinde tüm takip ettikleriniz takip edilecektir.

bu iki işlemden sonra takipçileriniz yeni hesabınıza yönlendirilecek ve yüklediğimiz liste ile de eski takip ettiklerinizi tekrar takip ediyor olacaksınız. takipçileriniz aradaki farkı isminiz dışında fark etmeyecek ve herhangi bir bildirim almayacaklardır.

rehberdeki bazı görseller doğrudan [docs.joinmastodon](https://docs.joinmastodon.org/user/moving/) üzerinden alınmıştır. metin bana aittir. istediğiniz gibi paylaşabilirsiniz.

sorularınız varsa veya fark ettiğiniz hatalar varsa: [@miv403@defcon.social](https://defcon.social/@miv403

miv403@duck.com
