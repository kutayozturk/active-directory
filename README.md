# Active Directory Nedir?

WINDOWS ACTIVE DIRECTORY
Active Directory, Microsoft tarafından özellikle Windows Server ve Client bilgisayar sistemleri için tasarlanmış olan içerisinde sunucu, client bilgisayar, kullanıcı ve yazıcı gibi bilgileri tutan bir dizin servisidir.
Bu servis içerisinde yer alan Group Policy yönetim aracı ile çeşitli kısıtlamalar yapabilir veya tek bir noktadan (merkezden) istedigimiz uygulamanın dağıtımını gerçekleştirebiliriz.

- Active Directory servisi, Domanin Controller olarak adlandırılan sunucu veya sunucular üzerinde tutulur.

- Veritabanı dosya ismi ise ntd.dit dosyasıdır.

- Bunubnla birlikte tüm işlemlerin geçici olarak yer aldığı, değişikliklerin veritabanına yazılmadan önce çeşitli sebeplerden ötürü saklandığı edb.log isimli dosya da, Active Directory servisinin çalışmasında kritik rol oynar.

## Active Directory Özellikleri
- Yönetilebilirlik
- Genişletilebilirlik
- Güvenlik Entegrasyonu
- Diğer Dizin Servisleriyle Birlikte Çalışma
- Güvenli Kimlik Doğrulama ve Yetkilendirme
- Group Policy ile Yönetim
- Dns ve Dhcp gibi Servislerle Birlikte Çalışabilme Özelliği

# Active Directory Mantıksal Yapısı
Active Directory'nin mantıksal katmanı veri deposunda bulunan bilgilerin nasıl görüleceğini belirler ve aynı zamanda o bilgilere erişimi denetler. Active Directory içerisinde kullanıcı ve yönetici kapsamında hiyerarşik bir yapı kurulmasına olanak verir.

- Domain
- Domain Tree
- Forest
- Organizational Unit
- Global Catalog
- LDAP Yapısı


## Active Directory Fiziksel Yapısı

Active Directory içerisinde fiziksel yapı, mantıksal yapıdan bağımsız bir mimariye sahiptir. Mantıksal yapı ile network kaynakları organize edilirken, fiziksel yapı ile network trafiğinin kontrolü ve konfigürasyonu gerçekleştirilebilir. Active Directory'nin fiziksel yapsını; DC (Domain Controller) ve Site'lar oluşuturur. 
- Site
- Domain Controller

## Active Directory Güvenlik Sorunları

Yapı içinde doğru şekilde kurgulanmamış olması birçok güvenlik sorununu beraberinde getirmektedir. Burada dikkat etmemiz gereken noktalar parola politikaları, hesap yetkileri, loglama yöntemleri ve aralıkları şeklinde bazı parametrelerdir.

## Active Directory Güvenliği

- Hesap Bilgilerinin Kontrol EDilmesi ve Değiştirilmesi
- Kritik Grup Üyeliklerinin Kontrol EDilmesi
- Yapı İçerisindeki Kullanıcı Hesaplarının Takibi
- Kimlik Doğrulama
- Lockout Yöntemi

## Active Directory loglama

Loglama yöntemi, yapılan tüm eylemlerin kayıt altına alınmasıdır. Bu yöntem ile yapılan tüm eylemler denetlenebilir ve kritik durumlarda bazı eylemleri tespit etmemizi sağlar.

Active Directory de yapı oldukça önemlidir. Bu yapıyı belirli aralıklarla takip etmemiz ve incelememiz gereklidir.

## Group Policy Management ile Güvenliğin Sağlanması

- Kontrol paneli erişimi
- Bilgisayarlara takılan cihazların denetimi
- Yazılım yüklenmesinin denetimi
- Parola kullanım süresi ve uzunluğu
- Komut satırı erişimi

