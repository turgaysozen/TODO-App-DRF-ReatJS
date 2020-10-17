# Startech Test Case

## Problem 1 (Kod Çalışması)

Kullanıcı yetkilendirmesi olan bir API ve önyüze sahip TODO List yapmanız beklenmektedir. 

---------

- Projenizde Django 3+, Django Rest Framework backend olarak kullanılmalıdır. Frontend kısmında Boostrap, jQuery kullanmanız beklenmektedir. *Vuejs veya ReactJS kullanımı bonus olarak değerlendirilecektir.*

- TODO List uygulamasında kullanıcı şu işlemleri yapabilmelidir:
  - Her kullanıcı kendine ait TODO ekleyebilir, silebilir ve güncelleyebilir
  
  - Kullanıcıya ait bütün listeyi görüntüleyebilir.

---------

- Sisteme kayıtlı tüm kullanıcıları listelenebilmeli
- Sisteme yeni kayıt yapılabilmeli

Proje dökümanı yazılması beklenmektdir

API erişiminde Token Authention kullanılması bonus olacaktır. 

## Problem 2 

> Bu problemde kod yazmanız beklenmemektedir. Açıklamayla beraber pseudo kod, akış diagramı gibi yöntemler de kullanabilirsiniz. Probleme yaklaşımınız bizim için önem taşımaktadır. 

OTP: One time password

T-OTP: Time based one time password

Normal şartlar altında sürekli çevrimiçi olan iki cihaz mevcut. Birer dakika aralıklarla, iki cihaz da birer adet T-OTP üretiyor. Birinci cihaz ürettiği T-OTP kodunu kullanıcının telefonuna sms olarak gönderiyor. Birinci cihazda üretilen kodun aynısı ikinci cihazda da üretildiğinden doğrulama gerçekleşirse (kullanıcı yanlış girmezse)  ikinci cihaz, kullanıcısının erişimine açılıyor. 

**Problem:**  İkinci cihazın internet bağlantısı uzun süre kesildiğinde, cihazın saat bilgisi zaman içerisinde doğruluğunu kaybedecektir. Bu sebeple, T-OTP çevrimdışı durumda kullanılamayacaktır.

**Soru:** Çevrimdışı durumda, sistemin güvenliğini korumak amacıyla nasıl bir çözüm önerirsiniz?

**Not:** Sistemi yetkisiz erişime açmadıkça istenilen yöntem kullanılabilir. Birinci ve ikinci cihazın kullanıcıları herhangi bir şekilde kodların oluşturulma algoritmasına sahip olmamalıdır.

-------

Proje tamamlandıktan sonra Github üzerinde private repo açılarak [Ahmet Özsönmez](https://github.com/aozsonmez) ve [Oktay Sabak](https://github.com/oktaysabak) contributor olarak eklenmelidir.