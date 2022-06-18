
# Week1Assignment

- **Soru 1: OOP nedir? Ne amaçlı kullanılır ?**
    
    - **OOP nedir ?**
        - OOP - Nesne Yönelik Programlama(Obejct-Oriented Programming) - Normal programlama yazılan prosedür veya funksiyonlar veriler üzerinde işlem yapıyorsa, OOP ise hem veri hem de işlev içeren nesneler oluşturmakla ilgilidir.

    - **Ne amaçlı kullanılır ?**
        - Kullanma amacı ise hızlı ve kolay yürütmek,
        - Açık (temiz) bir yapı olması sağlar,
        - Kod yazarken kendini tekrarlamamak için önleniyor DRY - "Don't repeat yourself" böylelikle kodu daha kolay okursun, değiştirisin veya hata bulursun (debug),
        - Daha az kod ve daha kısa geliştirme süresi ile tam yeniden kullanılabilir uygulamalar oluşturmak mümkün.

- **Soru 2: Polymorphism ne amaçlı kullanılır ?**

    - Polimorfizm "birçok form" anlamına gelir ve kalıtım yoluyla veya miras almak (inheritance) birbiriyle ilişkili birçok sınıfımız olduğunda ortaya çıkar. Başka bir sınıftan (**class**) miras aldığında o sınıfın öznitelikler ve metodların kullanılabilir, Polymorphism ise bu metodların farklı işlemler için kullanabilmektir (**override**) yani tek bir eylemi farklı şekillerde gerçekleştirmemizi sağlar. 

- **Soru 3: Bir metodun private, protected ya da public olması kavramlarını açıklayınız.**

    - **private**
        - Bir metodun private olduğunda tek bulunduğun sınıfında erişilebilir, nesne oluştururken ya da miras alınırken erişilemez.
    - **protected**
        - Bir metodun protected olduğunda bulunduğun sınıfın ve çocukların sınıflarında (child class) erişilebilir, nesne oluştururken erişilemez.
    - **public**
        - Bir metodun public olunca her yerden erişilebilir. 

- **Soru 4: (Abstraction) Soyutlama nedir ?**

    - Abstraction da bir sınıftır. Bu sınıftan nesne oluşturamazsın çünkü soyut bir sınıftır, ama sınıflardan miras alınabilir.
    - Abstract sınıfın içerisinde oluşturan metodlar, miras alan sınıflar ise bu metodları override etmesi lazım, metodların isimleri ve alan parametreler aynı olması gerekiyor, ek olarak child sınıf isteğe bağlı (optional) parametre ekleyebilir, bu metodların erişim değiştiricileri (access modifiers) ya abstract sınıfında tanımladığı erişim değiştirici gibi olmalı ya da daha az kısıtlı erişim değiştirici olmalı. 
