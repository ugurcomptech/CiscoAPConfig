# Cisco Access Point Config

![image](https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/9606a193-ce6c-418f-a1c9-1b97497bf2c4)


Burada ki görsel de "star topolojisi" ile yapılmış basit bir yönlendirme görüyorsunuz.  

- Manisada 4 tane bilgisayar, 1 tane telefon, 1 tane AP var
- Balıkesirde 5 tane bilgisayar, 1 tane printer, 1 tane AP var
- Manisa tarafında  AP'ye bir tane telefon bağlı
- Balıkesir tarafında AP'ye bir tane laptop bağlı


## AP Yapılandırması 

Access Pointinize şifre koymazsanız simulasyon yaparken başka bir yerde ki telefon/laptop bağlanabilir ve sorun çıkarabilir.

![image](https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/ea982aed-626f-4b1f-ae13-7f75fbe613f0)


Bu şifreyi telefona/laptopa da yazmanız gerekmektedir yoksa bağlanmayacaktır.

![image](https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/106a37bf-282f-4b4a-b00f-27ed85838d9f)



**Önemli:** Normal de Laptop da sadece ethernet kartı olur bunun için laptopu kapatıp **PT-LAPTOP-NM-1W** parçasını takmanız gerekiyor.

![image](https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/d55c1648-efc5-4fec-8c09-c5b0d5a6fb0c)


IP Config kısmına geliyoruz ve yapılandırmalarımızı yapıyoruz.


## Laptop
![image](https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/61498569-4916-4dcf-bdca-77224ff2a20c)

## Telefon
![image](https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/bc21c4de-a119-47f5-a51c-6b765e866503)


Şimdi Ping atmaya çalışalım ve paketin nasıl gittiğini görelim:


https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/8d38f647-b5de-411e-9952-de003edfbdda



Başarılı bir şekilde paketi gönderdik:

![image](https://github.com/ugurcomptech/CiscoAPConfig/assets/133202238/e19cd2f5-42c0-412c-92cf-71506599db7b)
