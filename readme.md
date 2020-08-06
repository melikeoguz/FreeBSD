### FreeBSD Nedir?

Merhaba arkadaşlar, bugün sizlere FreeBSD'nin yeni sürümü olan <code>FreeBSD 12.1</code> hakkında bilgi vereceğim. Yazıma başlamadan önce <b>FreeBSD nedir</b> ve <b>neden kullanılır</b> gibi soruları yanıtlamak istiyorum.

<h4><ins>FreeBSD Nedir ?</ins></h4>

FreeBSD bildiğiniz üzere [açık kaynak kodlu](https://www.biltektasarim.com/blog/acik-kaynak-kodu-nedir) ve topluluk tarafından geliştirilmiş bir işletim sistemidir. Adında bulunan <b>BSD</b> aslında <b>Berkeley Software Distribution</b>'nın kısaltmasıdır.

FreeBSD, hem kişisel bilgisayarlarımız için hem de ağ sunucuları için kullanılabilen güvenli bir işletim sistemidir. Kullanımının kolay olması ve diğer linux dağıtımlarından en önemli farkı <ins>Unix'den kopyalanmış bir işletim sistemi olmamasıdır</ins>. Gönüllü topluluk tarafından tamamen özgün geliştirilmiş bir sistemdir.

Peki FreeBSD neden bu kadar fazla kullanıcıya ulaşmıştır? FreeBSD'yi kullanan kullanıcılara bakıldığında başlangıç seviyesinden uzmanlık seviyesine kadar her seviyeye hitap eden, yüksek performanslı ve oldukça güvenlikli olması sebebi ile günümüzde popülaritesi artmış bir işletim sistemidir. 

Adını herkese duyurmuş, dünyaca ünlü şirketler arasında yer alan <b>Yahoo, Microsoft, Netflix, Sina, Yandex, Sony Japan, Cisco, Dell EMC Isilion</b> alt yapısında FreeBSD kullanmaktadır. Aynı zamandan birçok projede de bu işletim sistemi kullanılmaktadır. FreeBSD'nin <b>İnternet Servislerinin</b> bizlere sunduğu imkanlar şunlardır:

<ul>

<li>Web sunucuları</li>
<li>IPv4 ve IPv6 yönlendirmeleri</li>
<li>Firewalls ve NAT(ip maskeleme) ağ geçitleri</li>
<li>FTP sunucular</li>
<li>Email sunucular</li>

</ul>

FreeBSD grafikler için [X Window System](http://www.opengroup.org/tech/desktop/x-window-system/) kullanmaktadır. FreeBSD <code>Kerberos yetkilendirme, uçtan uca şifreleme ve güvenli RPC</code> özelliklerine sahiptir. Aynı zamanda USB desteği de sağlamaktadır.

<h4><ins>Niçin FreeBSD Kullanılır ?</ins></h4>

<li>FreeBSD yüksek güvenlikli bir işletim sistemi iken Windows işletim sisteminde oldukça fazla güvenlik açığı bulundurmaktadır. Virüslere, solucanlara ve hacker ataklarına karşı FreeBS'ye oranla daha savunmasızdır. </li>

<li>Ücretsiz ve kolay erişim imkanı tanıdığı için daha tercih edilebilir bir işletim sistemidir. </li>

<li>Linux'a göre daha yoğun bir trafiği karşılayabilecek potansiyeldedir.</li>
<li>Yüksek performanslı ve gelişmiş güvenlik güvenlik önlemlerini beraberinde getirir.
<li>FreeBSD beraberinde, ünlü internet sunucusu <b>Apache</b> 'yi getirir.</li>

<li>Grafiksel arabirim olarak çok gelişmiş olmasa da kendine özgün bir zarifliği vardır.</li>

<h4>Sanal Makinede FreeBSD Kurulumu</h4>


<b>1-</b> Öncelikle FreeBSD indirmek için [buraya tıklayınız](https://www.freebsd.org/where.html)</li></br>
**2-** Daha sonra aşağıdaki gife bakarak gereken adımları gerçekleştirip indirme işlemini tamamlayınız.</br>

![FreeBSD-download](assets/images/freebsd-download.gif)

**3-** Sıradaki adımı aşağıdaki gif yardımıyla gerçekleştirebilirsiniz.
> FreeBSD en az 2 gb bir ram belleğine ihtiyaç duymaktadır. Bu yüzden <b>Memory Size</b> kısmını en az 2000 mb yapmanız gerekmektedir. 

![Sanal Makine FreeBSD](assets/images/sanal-makine-freebsd.gif)

> Eğer <b>Değişken Boyut</b> seçeneğini kullanırsanız, sistemi kullanırken ayırdığınız boyutu aşsanız bile sisteme programınız yazılmaya devam eder. Eğer <b>Sabit Boyut</b> seçerseniz makine tarafından size bir uyarı mesajı gönderilecektir.

**4-** Şimdi ise **Ayarlar > Depolama** seçeneğine tıklayarak bir sürücü ekleyin. Bu sürücü 1.adımda indirmiş olduğumuz **FreeBSD iso dosyasıdır.**</br> 

![Adım](assets/images/adim.jpg)

**5-** Daha sonra aşağıdaki gifi referans alarak gereken adımları tamamlayınız.

![Sanal makine açıldı](assets/images/freebsd-once.gif)

**6-** Eğer bütün adımları tek bir video üzerinden izlemek isterseniz aşağıdaki videoya tıklamanız yeterlidir.

![FreeBSD Kurulumu](https://www.youtube.com/watch?v=N3CCVqsMxlQ)

Yazımı burada sonlandırarak herkese sağlıklı günler diliyorum..
