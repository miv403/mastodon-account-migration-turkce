# bir mastodon hesabı nasıl taşınır?

> bu rehber bir mastodon hesabını başka bir mastodon hesabına nasıl taşıyabileceğiniz ve yönlendirebileceğinizi göstermeyi amaçlamaktadır.

## neleri taşınabilir?

- takipçiler
- takip edilenler
- engellenen kişiler
- susturulan hesaplar
- yer imleri

## neleri taşınamaz?

gönderilerinizi taşıyamazsınız ama hesabınızın arşivini isteyerek dışarı aktarabilirsiniz. indirdiğiniz .tar.gz uzantılı arşiv dosyasının içinde "outbox.csv" adlı dosyada tüm iletilerinizi (tootlar ve doğrudan mesajlar) bulabilirsiniz. ayrıca hesabınıza dair diğer tüm veriler arşiv dosyasının içinde mevcuttur.

isterseniz taşımadan önce eski hesabınızdaki gönderileri yeniden paylaşarak (boostlayarak) yeni hesabınızda gözükmesini sağlayabilirsiniz.

### #1 taşınmak istediğiniz sunucuda hesap açın

taşınmak istediğiniz sunucuya karar verdikten sonra o sunucuda bir hesap açın. daha önce açtığınız hesabı açmaktan hiçbir farkı yoktur. unutmayın bu açtığınız hesap önceki hesabınızdan tamamen farklı bir hesap. kullanıcı adını aynı seçseniz bile verileriniz başka bir sunucuda tutulacak ve erişeceğiniz adres farklı olacak.

> eskihesabim@eski.mastodon > yenihesabım@yeni.mastodon

> eğer eski kullandığınız kullanıcı adı müsait ise aynı adı da alabilirsiniz:
> favoritakmaismim@eski.mastodon > favoritakmaismim@yeni.mastodon

### #2 hesap takma adı oluşturma

yeni hesabınıza bir tarayıcı üzerinden giriş yapın. hesap sekmesini ve altındaki hesap ayarları sekmesini bulun. sayfanın aşağısındaki "farklı bir hesaptan taşınma" başlığı altındaki bağlantıya tıklayın.

![hesap ayarları / hesap takma adı](./img-src/hesap-ayarlari-farkli-bir-hesaptan-tasima-800x600.png)

![hesap takma adı](./img-src/hesap-takma-adlari-800x600.png)

buraya eski hesabınızın kullanıcı adını girin ve takma ad oluştur adlı düğmeye tıklayın.

> kutucuğa eskihesabim@eski.mastodon kullanıcı adınızı girmeniz gerekiyor.

### #3 verileri dışa aktarma

tarayıcınızdan taşınacak/yönlendirilecek olan (yani eski hesabınız) hesaba giriş yapın. ayarlar kısmına girin. içe ve dışa aktar adlı sekmeye ve sonra veriyi dışa aktar sekmesine tıklayın. takip edilen yazan satırın sonundaki "csv" düğmesine tıklayın ve "following_accounts.csv" adlı dosyayı kaydedin. bu dosya takip ettiğiniz kişilerin listesini içerir. yerini unutmayın lazım olacak. ayrıca bu alanda isterseniz diğer verilerinizi de indirebilirsiniz veya arşivinizi isteyebilirisiniz.

![veriyi dışa aktar / takip edilenler listesi](./img-src/veriyi-disa-aktar-takip-edilen-800x600.png)

> işaretli olan csv yazısına tıklayın ve takip edilenler listesini indirin.


### #4 eski hesabınızı yeni hesaba yönlendirme

eski hesabınıza bir tarayıcı üzerinden giriş yapın ve ayarları açın. hesap sekmesi altındaki hesap ayarları sekmesinii açın. sayfanın aşağısındaki "farklı bir hesaba taşıyın" adlı başlığın altındaki bağlantıya tıklayın.

isterseniz uyarıları tekrar okuyup işlemi yapmak isteyip istemediğinizden emin olabilirsiniz.

buradaki kutucuklara yeni hesabınınızın kullanıcı adını ve eski hesabınızın parolasını girin. takipçileri taşı düğmesine tıkladıktan tüm takipçileriniz yeni hesabınıza yönlendirilecek.

bu işlem uzun sürebilir. nihayetinde tüm takipçileriniz herhangi bir bildirim almadan yeni hesabınızı takip ediyor olacak.

![hesap ayarları / farklı bir hesaba taşıyın](./img-src/hesap-ayarlari-farkli-bir-hesaba-tasiyin-800x600.png)

![hesap taşıma](./img-src/hesap-tasima-800x600.png)

> kutucuğa yenihesabim@yeni.mastodon kullanıcı adını ve eskihesabim@eski.mastodon adlı hesaba ait parolayı girmelisiniz.

nihayetinde eski profilinizde başka bir profile yönlendirildiğine dair bir bilgilendirme mesajı ve eski hesabınıza giriş yaptığınızda sizi ayarlar kısmına yönlendiriyor olması gerekiyor.

bu işlemleri başarıyla yaptığınız anlamına gelir. takipçilerinizin tamamı bir süre içinde yeni hesabınıza aktarılmış olacaktır. 

![hesap yönlendiriliyor](./img-src/hesap-yonlendiriliyor-800x600.png)

### #5 takip edilenleri aktarma

yeni hesabınıza giriş yapın ve ayarları açın. içe ve dışa aktar sekmesinin altındaki içe aktar sekmesini açın.

![içe aktarma](./img-src/veriyi-ice-aktar-takip-edilen-800x600.png)

takip edilenler listesi seçeneğini işaretleyin. gözat düğmesine basıp daha önce indirmiş olduğunuz "following_accounts.csv" adlı dosyayı seçin. sonra yükle düğmesine tıklayın. bu eski hesabınızdaki takip ettiğin herkesi yeni hesabınızda da takip etmenizi sağlayacak. bu işlem uzun sürebilir. nihayetinde tüm eski hesabınızdaki takip ettiklerinizi yeni hesabınızda da takip ediyor olacaksınız.

bu menü içerisinden daha önce aktarmak istediğiniz diğer verileri de aktarabilirsiniz. içeri aktarma türü altındaki açılır listeden ilgili seçeneği işaretleyip ilgili veriyi yüklemeniz yeterli.

***

görseller [GIMP](https://www.gimp.org) ile düzenlenmiştir.

ingilizce resmi rehber için [adresini](https://docs.joinmastodon.org/user/moving/) ziyaret edebilirsiniz.

sorularınız varsa [@miv403@defcon.social](https://defcon.social/@miv403) ve [miv403@duck.com](mailto:miv403@duck.com) adresleri üzerinden iletişime geçebilirsiniz.

> bu rehber resmi ingilizce rehber temel alınarak miv403 tarafından yazılmıştır. herhangi bir çeviri yoktur.