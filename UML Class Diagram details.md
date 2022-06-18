### UML Class Diagram
Bir e-ticaret projesinde, sisteme giriş yapacak farklı kullanıcı türleri mevcuttur. Bu türler üç başlıkta toplanabilir. Müşteri (Client), Satıcı (Merchant), Sistem Yöneticisi (Admin) Her başlıktaki kullanıcı türleri için aşağıdaki koşullar mevcuttur:

- Tüm kullanıcıların TCKN numarası olmalıdır.
- Tüm kullanıcıların ad soyad ve e-posta bilgisi olmalıdır.
- Müşterilerin eşsiz (unique) müşteri no olmalıdır.
- Satıcıların eşsiz (unique) satici no olmalıdır.
- Sistem yöneticilerinin kullanıcı idsi olmalıdır.
- Satıcıların cep telefonu onaylı olup olmadığı bilgisi olmalıdır

- name - ad, surname - soyad, checkPhoneNo - telefon numarası onaylı olup olmadığını kontrol etmek için

<img src="https://github.com/EnUygunPatikaBootCamp/week1-EagleGazii/blob/main/UML%20Class%20Diagram%20-%20PHP%20Enuygun%20(18.06.2022).drawio.png?raw=true"/>

- Tüm kullanıcıların burda tckn numarasi ve ad, soyad, eposta ayni olduğu için abstract bir sınıf oluşturarak her sınıfta aynı verileri tekrar yazmak "OOP'nin bir özelliklerinden kendini tekrarlamya önlenir-don't repeat yourself", sonuçta bu yapıda müşteri, satıcı veya yönetici her biri bir kullanıcı olduğuna göre User abstract sınıfı oluşturabiliriz ve önce saydığım sınıflar User sınıfından miras alarak kendi sınıfın içerisinde bu değişkenler bulunur.
- Müşterilerin (Client), Satıcıların (Merchant) kendi öznitellikler olarak bu ikisi id'leri unique olmalı, ve Satıcıların (Merchant) içinde ek olarak bir metodu olup satıcının telefon numarası geçerli olup olmadığını belirlenir. Yönetici (Admin) öznitelliğin olarak id'si var.  
