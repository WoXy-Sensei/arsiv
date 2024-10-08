# MK4i

MK4i, [MK4](../mk4.md) modülünün ters çevrilmiş motorlu, köşe tabanlı versiyonudur. MK4i modülü motorları daha alçak bir konuma taşır, Toplam yükseklik ve ağırlık merkezi daha düşüktür. MK4i modülü ayrıca daha geniş bir dingil mesafesi için tekerleği şasinin köşesine doğru hareket ettirerek daha dengeli bir robot elde edilmesini sağlar. Tekerlek, şasinin tipik olarak işgal edeceği bir alana taşındığından, MK4i şasiyi düzgün bir şekilde kutulamak için ikincil bir plaka içerir.

***

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

***

## Özellikleri

* Eksen içi yönlendirme enkoderi (sıfır boşluk, modül enkoder ofsetini sıfırlamadan sökülebilir/yeniden monte edilebilir)
* Tüm plakalar 7075-T6 alüminyumdan yapılmıştır
* Tüm dişliler çeliktir
* Tüm hareketli parçalar üst plaka altında korunmaktadır
* Çerçeve içindeki kutuya ikincil plaka dahildir
* Alt sistemler için ana plaka üzerinde 10-32 montaj delikleri (örn. kolektör)
* 15mm genişliğinde direksiyon kayışı
* Direksiyon enkoderini korumak için enkoder koruması
* Önceki Swerve Drive Specialties modülleri ile aynı şasiden zemine yükseklik
* [MK4](../mk4.md) modülü ile aynı L1, L2 ve L3 tahrik oranları (ayrı olarak temin edilebilen 16T Tahrik Pinyonu Adaptör Kiti kullanıldığında [MK4n](../mk4n.md) ile aynı L1+, L2+ ve L3+ tahrik oranları)
* 3D baskılı parça yok
* Kablo bağı “çıkıntıları” kablo bağlarını yerinde tutar
* Alt ve üst montajlı şasi seçenekleri
* Boyuna kesilmiş, delinmiş ve tekerleğe önceden takılmış tekerlek sırtı içerir. Bu modül artık sırt ömrünü daha da uzatan siyah neopren sırtla (resimde mavi nitril) birlikte gönderilmektedir.
* Modülü robota monte etmek için donanım da dahil olmak üzere tüm donanımı içerir

{% hint style="warning" %}
MK4i modülü, [MK4](../mk4.md) modülü ile birçok ortak parçaya sahiptir. [MK4](../mk4.md)'ü MK4i'ye dönüştürmek için kitler mevcuttur. MK4i modülü monte edilmemiş olarak gönderilir ve aşağıdaki bileşenler dahil değildir:
{% endhint %}

* Tahrik motoru (NEO, NEO Vortex, Falcon 500 veya Kraken X60)
* Direksiyon motoru (NEO, NEO Vortex, Falcon 500 veya Kraken X60)
* Direksiyon enkoderi (CTRE CANcoder, Thrifty Absolute Magnetic Encoder, Redux HELIUM Canandcoder veya eşdeğeri)

{% hint style="danger" %}
Not: Yukarıdaki direksiyon enkoderleri, Swerve Modülünün Orta Kolonuna takılan ⌀.250 “x 0.500” mıknatısla birlikte gelir. Bu mıknatıs Swerve Modülü kitine dahil değildir.
{% endhint %}

{% hint style="warning" %}
CIM motorları daha büyük çapları nedeniyle MK4i ile uyumlu değildir. (kısmen [:D](https://www.chiefdelphi.com/t/7444-charged-up-robot-showcase-cim-neo-mk4i-swerve-drive-chassis/431371) <-)
{% endhint %}

* MK4i'nin direksiyon dişli oranı 150/7:1'dir.

MK4i 3 farklı tahrik dişlisi oranında mevcuttur. Aşağıdaki tablo [NEO](../../motorlar/fircasiz-motorlar/neo-v1/) ve [Falcon 500](../../motorlar/fircasiz-motorlar/falcon.md) motorlarla tahrik dişlisi oranlarını ve serbest hızları göstermektedir. L1 ve L2 oranları en popüler oranlardır ve standart tam ağırlık yarışma robotları için uygundur. L3 oranı daha agresiftir ve hafif robotlar için önerilir.

{% hint style="info" %}
Ayrıca temin edilebilen 16T Tahrik Pinyonu Adaptör Kiti kullanılarak \~%14 artırılabilir.
{% endhint %}

![](https://cdn.shopify.com/s/files/1/0065/4308/1590/files/14T\_Gear\_Ratios.png?v=1723760292)

![](https://cdn.shopify.com/s/files/1/0065/4308/1590/files/MK4\_Free\_Speeds.png?v=1723760292)

{% hint style="warning" %}
Modül, 25x50mm ölçülerinde profile montelenmektedir. Monteleme civataları paket içeriğinde bulunuyor.
{% endhint %}

{% hint style="info" %}
Modül ana plakası tipik olarak robot şasisinin üzerine monte edilir, ancak yerden yüksekliği en üst düzeye çıkarmak için şasiyi modül ana plakasının üzerine monte etmek için de boşluk vardır.
{% endhint %}

