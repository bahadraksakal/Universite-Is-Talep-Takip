# Universite-Is-Talep-Takip <br>
UI kısmında hem web hem de telegram botu kullanılan bir web projesi.  <br>
Bu proje şuan doktora tezi olarak geliştirilmeye devam edildiği için pek fazla bilgi paylaşamıyorum.  <br>
Genel olarak projede iş-talep-takip sisteminin daha kullanışlı olması amaçladık. Bu nedenle Telegram API yardımıyla hem sistemdeki personellerin, hem adminlerin, hemde diğer kullanıcıların telegram bot üzerinden iş-talep-takip sistemini kullanmasını sağladık.  <br>
 <br>
Bu projede;
- Veri Tabanı Tasarımı,
- Veri Tabanı,
- Back-End,
- Front-End,
- Telegram Bot,
tarafımca yapılmıştır.
 <br>
Sistemi kısaca anlatmak gerekirse örneğin: <br>
a)üniversitede bir sınıfta projeksiyon HDMI kablosunun ucu kırılmış olsun. <br>
b)Bunu fark eden kişi fotoğrafını çekip telegram botuna gönderiyor ve talebini yazıyor örn(Projeksiyon kablosu fotoğrafta görüldüğü üzere kırılmıştır, değiştirmenizi talep ediyorum). <br>
c)Daha sonra bu talep , talepleri dağıtan birimin önüne düşüyor ve bu birim talebi ilgili başkanlığa yönlendiriyor <br>
d)İlgili başkanlık, gelen talebi; ilgili müdürlüğe veya direkt ilgili personele yönelendiyor. <br>
e)Önüne iş talebi düşen personel, olay yerine gidip sorunu çözüyor ve telegram bot üzerinden ilgili adımları takip ederek talebi kapatıyor. Bu kapatma işleminde  projeksiyonun çalıştığına dair bir fotoğrafı bota yolluyor ve gerekli açıklamayı bota yazıyor. <br>
d)Gönderilen fotoğraf ve mesajla birlikte talep kapanıyor ve onaylanmak üzere bir üst birime düşüyor. <br>
f)Bir üst birim cevabı yetersiz bulup, talebi ilgili personele geri yollayabilir veya onaylar. <br>
g)Talep onaylandığı durumda, talebin cevabı ve ekleri(ses,konum,fotoğraf,belge); talebi açmış olan kullanıcıya telegram üzerinden mesaj olarak iletiyor.
(gg/aa/yyyy tarihli talebiniz kapanmıştır vs....). <br>
Not: Geliştirmiş olduğum bu projede yukarıda bahsi geçen işlemler aynı zamanda web üzerinden de yapılabiliyor, fakat fotoğraf çekip yollama gibi işlemlerin kolaylaştırması açısından telegram bot daha pratik oluyor. <br>
Not-2: Personel ve Adminler telegram botta bir sefere mahsus oturum açıyor. Bu oturum tek kullanımlık bir key yardımıyla açılıyor. Bu konuda detaylı anlatım raporumda mevcuttur. <br>
Daha detaylı bilgi için ekteki raporumu okuyabilirsiniz. <br>
Hala sorularınız varsa bana mailimden ulaşabilirsiniz. <br>



