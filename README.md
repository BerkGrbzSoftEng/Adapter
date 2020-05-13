 # Adapter Tasarım Kalıbı
**Adapter tasarım kalıbı:**</br>
Temelde birbiriyle uyumsuz ancak aynı işi yapması
öngörülen iki interface'in haberleştirilmesi için
kullanılır.

Adapter tasarım kalıbının kullanımı, sizin
uygulamalarınızın yeni bileşenlerin kullanımına
izin verdiği gibi aynı zamanda sizin var olan
arayüzlerinizi kullanmanızı da sağlar.

Önemli: Yeni bir sürüm geldiğinde, yapmanız
gereken sadece Adapter’i değiştirmektir.
</br>

![Adapter UML](https://drive.google.com/open?id=1nhKq3KgPvkvqwLsfKqssH86vZeEAVI_V)

- **Adapter**: 
> Framework’un kullanacağı metotları
tanımlayan arayüz.

- **Adaptee**: 
> Adapte edilecek tipin metotlarını
tanımlayan arayüz. Bu arayüz, çalışma zamanında
dinamik olarak belirli Adaptee’nin yüklenmesine
izin verir.

