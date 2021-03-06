# Object Oriented Programing



## Üniversite Yönetim Sistemi

Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.

Departmanlara ait ofisler vardır.

Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.

Her çalışan bir ofiste çalışır.

Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.

![](https://github.com/yasemingurbuz/ObjectOrientedPrograming/blob/main/%C3%9Cniversite.png)

### Hayvanat Bahçesi

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

- Hayvanlar:
  - Atlar (atlar, zebralar, eşekler vb.),
  - Kedigiller (kaplanlar, aslanlar vb.),
  - Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
- Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
  - tür adı, ağırlığı, yaşı vb.
- Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
- Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

![](https://github.com/yasemingurbuz/ObjectOrientedPrograming/blob/main/hayvanbah%C3%A7esi.png)

## Uçuş Yönetim Sistemi

Uçuşların ve pilotların yönetimi için bir sistem tasarlayın.

- Havayolu şirketleri uçuşları gerçekleştirir. Her havayolunun bir kimliği vardır.
- Havayolu şirketi, farklı tipteki uçaklara sahiptir.
- Uçaklar çalışır veya onarım durumunda olabilir.
- Her uçuşun benzersiz kimliği, kalkacağı ve ineceği havaalanı, kalkış ve iniş saatleri vardır.
- Her uçuşun bir pilotu ve yardımcı pilotu vardır ve uçağı kullanırlar.
- Havaalanlarının benzersiz kimlikleri ve isimleri vardır.
- Havayolu şirketlerinin pilotları vardır ve her pilotun bir deneyim seviyesi mevcuttur.
- Bir uçak tipi, belirli sayıda pilota ihtiyaç duyabilir.

Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.

![](https://github.com/yasemingurbuz/ObjectOrientedPrograming/blob/main/havayolu.png)

## Online Film Sitesi

Online film satan veya kiralayan uygulamanın sistemini tasarlayın.

- Uygulamada filmler listenebilir, sıralanabilir ve kullanıcılar uygulamaya abone olabilir.
- Kullanıcılar abonelik için sistem üzerinden kredi satın alır.
- Sadece abone olan kullanıcılar, kredileri ile film kiralayabilir ve kiraladığı filmin kredi bedeli kadar hesabından düşülür.
- Normal kullanıcılar ve aboneler film satın alabilirler.
- Eğer film mevcut değilse ise talep edilebilir.

Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.

![](https://github.com/yasemingurbuz/ObjectOrientedPrograming/blob/main/film.png)

