## ikJet Human Resources


### <span style="color:red;">Proje Tanıtımı</span>
ikJet Human Resources, insan kaynakları süreçlerini dijital ortamda yönetmek için tasarlanmış kapsamlı bir otomasyon sistemidir. Bu proje, farklı kullanıcı rollerine göre yetkilendirme ve yönetim fonksiyonlarını içerir. Proje, admin, İK yöneticisi ve personel olmak üzere üç ana kullanıcı rolünü destekler.

### Kullanıcı Rolleri ve İşlevler

#### Client (Müşteri) Arayüzü:

Siteye giriş yapmadan otomasyon hakkında ve bizim hakkımızda bilgiler sunar.
Giriş yap butonuyla kullanıcıyı login ekranına yönlendirir.
Kullanıcı, e-posta ve şifresiyle giriş yaparak JWT token alır ve rolüne göre uygun panele yönlendirilir.

#### Admin Paneli:

Admin, e-posta ve şifresiyle giriş yaptıktan sonra şirketler ekleyebilir ve bu şirketlere İK yöneticisi atayabilir.
Şirketlere ait CRUD işlemleri yapabilir ve sitenin genel yönetimini sağlar.


#### İK Yönetici Paneli:

İK yöneticisi, kendi e-posta ve şifresiyle giriş yaparak şirketindeki personelleri listeleyebilir ve bu personellerle ilgili CRUD işlemlerini gerçekleştirebilir.
İzin, avans ve harcama taleplerini inceleyebilir ve onay/red verebilir.


#### Personnel (Personel) Paneli:

Personel, e-posta ve şifresiyle giriş yaptıktan sonra kendi izin, avans ve harcama taleplerini filtreleyebilir (onay bekleyenler, iptal edilenler, onaylananlar, reddedilenler).
Yeni talepler oluşturabilir.


#### Özellikler

#### Kullanıcı Yönetimi: Kullanıcı oluşturulduğunda şifre ve e-posta otomatik olarak oluşturulur ve kullanıcıya e-posta gönderilir. E-posta onaylandığında kullanıcı sisteme giriş yapabilir. 

#### Şifre Sıfırlama: Kullanıcılar, şifremi unuttum özelliği ile yeni şifre oluşturabilir ve bu şifre e-posta ile kendilerine gönderilir.

#### İzin ve Talepler: İK yöneticisi taleplerle ilgili işlemleri yönetebilir.


#### API Sunucusu

Bu proje, ikJetServer-API adlı bir API sunucusuna bağlıdır. API sunucusu, uygulamanın arka plan işlemlerini yönetir ve RESTful API sağlar.

<p align="center">
  <a href="https://github.com/BurakGonca/IkJetServer-API">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" style="width:50px;">
  </a>
</p>



#### Proje Tanıtım Videosu
<p align="center"> <a href="https://www.youtube.com/watch?v=W985E0gYhBE&list=PLHXbVmnbJxz6Th2LDvgFmKOEBEnVgtJJq"> <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube Logo" style="width:50px;top:10px;left:10px;"> <img src="https://img.youtube.com/vi/W985E0gYhBE/maxresdefault.jpg" alt="ikJet Tanıtım Videosu" style="width:100%;max-width:600px;"> </a> </p>
