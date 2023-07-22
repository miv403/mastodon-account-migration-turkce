# Bir Mastodon Hesabı Nasıl Taşınır?

> Bu rehber, bir Mastodon hesabını başka bir Mastodon hesabına nasıl taşıyabileceğiniz ve yönlendirebileceğinizi göstermeyi amaçlamaktadır.

## Neler Taşınabilir?

- Takipçiler
- Takip edilenler
- Engellenen kişiler
- Susturulan hesaplar
- Yer imleri

## Neler Taşınamaz?

Gönderilerinizi taşıyamazsınız, fakat hesabınızın arşivini isteyerek dışarı aktarabilirsiniz. İndirdiğiniz ``.tar.gz`` uzantılı arşiv dosyasının içinde ``"outbox.csv"`` adlı dosyada tüm iletilerinizi (tootlar ve direkt mesajlar) bulabilirsiniz. Ayrıca, hesabınıza dair diğer tüm veriler arşiv dosyasının içinde mevcuttur.

İsterseniz, taşımadan önce eski hesabınızdaki gönderileri yeniden paylaşarak (boostlayarak) yeni hesabınızda gözükmesini sağlayabilirsiniz.

### 1. Taşınmak İstediğiniz Sunucuda Hesap Açın

Taşınmak istediğiniz sunucuya karar verdikten sonra o sunucuda bir hesap açın. Daha önce açtığınız hesabı açmaktan hiçbir farkı yoktur. Unutmayın, bu açtığınız hesap önceki hesabınızdan tamamen farklı bir hesap. Kullanıcı adını aynı seçseniz bile verileriniz başka bir sunucuda tutulacak ve erişeceğiniz adres farklı olacak.

> eskihesabim@eski.mastodon → yenihesabim@yeni.mastodon

> Eğer eski kullandığınız kullanıcı adı müsait ise aynı adı da alabilirsiniz:
favoritakmaismim@eski.mastodon → favoritakmaismim@yeni.mastodon

### #2 Hesap Takma Adı Oluşturma

Yeni hesabınıza bir tarayıcı üzerinden giriş yapın. ``Hesap`` sekmesini ve altındaki ``hesap ayarları`` sekmesini bulun. Sayfanın aşağısındaki ``Farklı bir hesaptan taşınma`` başlığı altındaki bağlantıya tıklayın.

![hesap ayarları / hesap takma adı](./img-src/hesap-ayarlari-farkli-bir-hesaptan-tasima-800x600.png)

![hesap takma adı](./img-src/hesap-takma-adlari-800x600.png)

Buraya eski hesabınızın kullanıcı adını girin ve ``takma ad oluştur`` adlı düğmeye tıklayın.

> Kutucuğa eskihesabim@eski.mastodon kullanıcı adınızı girmeniz gerekiyor.

### 3. Verileri Dışa Aktarma

Tarayıcınızdan, taşınacak/yönlendirilecek olan (yani eski hesabınız) hesaba giriş yapın ve ayarlar kısmına girin. ``İçe ve dışa aktar`` adlı sekmeye ve sonra ``veriyi dışa aktar`` sekmesine tıklayın. Takip edilen yazan satırın sonundaki ``csv`` düğmesine tıklayın ve ``following_accounts.csv`` adlı dosyayı kaydedin. Bu dosya takip ettiğiniz kişilerin listesini içerir, yerini unutmayın lazım olacak. Ayrıca bu alanda isterseniz diğer verilerinizi de indirebilirsiniz veya arşivinizi isteyebilirisiniz.

![veriyi dışa aktar / takip edilenler listesi](./img-src/veriyi-disa-aktar-takip-edilen-800x600.png)

> İşaretli olan csv yazısına tıklayın ve takip edilenler listesini indirin.


### 4. Eski Hesabınızı Yeni Hesaba Yönlendirme

Eski hesabınıza bir tarayıcı üzerinden giriş yapın ve ayarları açın. Hesap sekmesi altındaki ``hesap ayarları`` sekmesini açın. Sayfanın aşağısındaki ``farklı bir hesaba taşıyın`` adlı başlığın altındaki bağlantıya tıklayın.

İsterseniz uyarıları tekrar okuyup işlemi yapmak isteyip istemediğinizden emin olabilirsiniz.

Buradaki kutucuklara yeni hesabınızın kullanıcı adını ve eski hesabınızın parolasını girin. ``Takipçileri taşı`` düğmesine tıkladıktan sonra tüm takipçileriniz yeni hesabınıza yönlendirilecek.

Bu işlem uzun sürebilir. Nihayetinde, tüm takipçileriniz herhangi bir bildirim almadan yeni hesabınızı takip ediyor olacak.

![hesap ayarları / farklı bir hesaba taşıyın](./img-src/hesap-ayarlari-farkli-bir-hesaba-tasiyin-800x600.png)

![hesap taşıma](./img-src/hesap-tasima-800x600.png)

> Kutucuğa yenihesabim@yeni.mastodon kullanıcı adını ve eskihesabim@eski.mastodon adlı hesaba ait parolayı girmelisiniz.

![hesap yönlendiriliyor](./img-src/hesap-yonlendiriliyor-800x600.png)

En sonunda, eski profilinizde başka bir profile taşındığınıza dair bir bilgilendirme mesajı, ve eski hesabınıza giriş yaptığınızda sizi ayarlar kısmına yönlendiriyor olması gerekiyor.

Bu, işlemleri başarıyla yaptığınız anlamına gelir. Takipçilerinizin tamamı bir süre içinde yeni hesabınıza aktarılmış olacaktır. 

### 5. Takip Edilenleri Aktarma

Yeni hesabınıza giriş yapın ve ayarları açın. ``İçe ve dışa aktar`` sekmesinin altındaki ``içe aktar`` sekmesini açın.

![içe aktarma](./img-src/veriyi-ice-aktar-takip-edilen-800x600.png)

``Takip edilenler listesi`` seçeneğini işaretleyin. Gözat düğmesine basıp, daha önce indirmiş olduğunuz ``following_accounts.csv`` adlı dosyayı seçin ve yükle düğmesine tıklayın. Bu işlem uzun sürebilir. Sonucunda, eski hesabınızda takip ettiğiniz kişileri yeni hesabınızda da takip ediyor olacaksınız.

Bu menü içerisinden daha önce aktarmak istediğiniz diğer verileri de aktarabilirsiniz. İçeri aktarma türü altındaki açılır listeden istediğiniz seçeneği işaretleyip ilgili veriyi yüklemeniz yeterli.

***

Görseller [GIMP](https://www.gimp.org) ile düzenlenmiştir.

İngilizce resmi rehber için [burayı](https://docs.joinmastodon.org/user/moving/) ziyaret edebilirsiniz.

Sorularınız varsa, [@miv403@defcon.social](https://defcon.social/@miv403) ve [miv403@duck.com](mailto:miv403@duck.com) adresleri üzerinden iletişime geçebilirsiniz.

> Bu rehber, resmi ingilizce rehber temel alınarak miv403 tarafından yazılmıştır, herhangi bir çeviri yoktur.
