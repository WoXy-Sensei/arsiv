# MK4n

{% hint style="danger" %}
ÖNEMLİ: Tipik bir aktarma organındaki bitişik MK4n Saptırma Modülleri birbirinin aynısıdır ve sonuç olarak iki kit düzeni vardır: “A” ve ‘B’. Nasıl sipariş edildiklerini incelemek ve doğru kodlayıcı yapılandırmasını aldığınızdan emin olmak için aşağı kaydırın.
{% endhint %}

***

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

***

MK4n Swerve Modülü, kanıtlanmış [MK4i ](../mk4i/)mimarisini yeni bir form faktörüne dönüştürür. Dar tarafın çerçeve elemanının içinde sadece 10,16 cm genişliğinde olmasıyla, etkinleştirmeye yardımcı olur.

* Saptırma modülleri arasında geniş oyun parçası girişleri.
* Kompakt aktarma organları (44,45 cm genişliğinde bir aktarma organında düz monte edilmiş bir FRC pil barındırır).

[MK4i](../mk4i/) ile karşılaştırıldığında ilave işlevsel farklılıklar şunlardır:

* 0,25“ mıknatıs kodlayıcıları desteklemenin ötesinde 0,5” altıgen kodlayıcıları da destekler. Altıgen kodlayıcı bu Merkez Kolonu kullanır.
* Daha yüksek tahrik ve direksiyon hızları için 16T tahrik ve direksiyon pinyon dişlileri.
* Eklenecek kapaklar için motor plakasında 10-32 dişli delikler.

{% hint style="info" %}
Lütfen unutmayın:

* NEO Vortex kiti, 8mm anahtarlı mile sahip [NEO Vortex](../../motorlar/fircasiz-motorlar/neo-v1/neo-vortex.md) motorlar için çalışır.
* Falcon 500 kiti öncelikle [Falcon 500](../../motorlar/fircasiz-motorlar/falcon-500.md) motoru içindir. Falcon spline şaftlı [NEO Vortex ](../../motorlar/fircasiz-motorlar/neo-v1/neo-vortex.md)motor için de çalışabilir, ancak şaft ara parçaları dahil değildir (Falcon motorlarla birlikte verilir) ve Yarım Daire Ara Parçası kiti de gereklidir.
{% endhint %}

[MK4i](../mk4i/) Swerve Modülü gibi MK4n de şunları içerir:

* Eksen içi yönlendirme enkoderi (dahil değildir). Sıfır boşluk ve modül, enkoder ofsetini sıfırlamadan sökülebilir/yeniden monte edilebilir
* Tüm plakalar 7075-T6 alüminyumdan yapılmıştır
* Tamamen çelik dişliler
* Çerçeve içindeki kutuya ikincil plaka dahildir
* Alt sistemler için ana plaka üzerinde 10-32 montaj delikleri (örn. kolektör)
* CANcoder (veya eşdeğeri) direksiyon enkoderini korumak için enkoder koruması
* [MK4](../mk4.md) ve [MK4i](../mk4i/) Swerve Modülleri ile aynı çerçeveden zemine yükseklik
* 16T Tahrik Pinyon Dişlisi Adaptör Kiti ile donatılmış MK4i Swerve Modülü ile aynı L1+, L2 ve L3+ tahrik oranları
* 3D baskılı parça yok
* Boyuna kesilmiş, delinmiş ve Billet Jant seçeneğine önceden takılmış jant dişi içerir
* Modülü robota monte etmek için donanım da dahil olmak üzere tüm donanımı içerir\


MK4n Swerve Modülü, [MK4i](../mk4i/) Swerve Modülü ile birçok ortak parçaya sahiptir ve dönüştürme kiti mevcuttur.

MK4n modülü monte edilmemiş olarak gönderilir ve aşağıdaki bileşenler dahil değildir:

* **Tahrik motoru** ([NEO](../../motorlar/fircasiz-motorlar/neo-v1/), [NEO Vortex](../../motorlar/fircasiz-motorlar/neo-v1/neo-vortex.md),[ Falcon 500](../../motorlar/fircasiz-motorlar/falcon-500.md) veya [Kraken X60](../../motorlar/fircasiz-motorlar/kraken-x60.md))
* Direksiyon motoru (NEO, NEO Vortex, Falcon 500 veya Kraken X60)
* Direksiyon kodlayıcı (0,25” mıknatıs kodlayıcı: CTRE CANcoder, Thrifty Absolute Magnetic Encoder, Redux HELIUM Canandcoder veya eşdeğeri; 0,5” hex enkoder: REV Through Bore Enkoder veya eşdeğeri)

{% hint style="warning" %}
Not: Yukarıdaki direksiyon 0,25” mıknatıslı enkoderler, Swerve Modülünün Orta Kolonuna takılan ⌀.250 ‘x 0,500’ mıknatısla birlikte gelir. Bu mıknatıs Swerve Modülü kitine dahil değildir.
{% endhint %}

[CIM ](../../motorlar/fircali-motorlar/cim.md)motorları daha büyük çapları nedeniyle MK4n ile uyumlu değildir.

MK4n'nin direksiyon dişli oranı 18,75:1'dir. MK4n 3 farklı tahrik dişlisi oranına sahiptir. Aşağıdaki tablolar tahrik dişlisi oranlarını ve serbest hızları özetlemektedir.

![](https://cdn.shopify.com/s/files/1/0065/4308/1590/files/16T\_Gear\_Ratios.png?v=1723760292)

![](https://cdn.shopify.com/s/files/1/0065/4308/1590/files/16T\_Free\_Speeds.png?v=1723760292)

{% hint style="warning" %}
Modül, 25x50mm ölçülerinde profile montelenmektedir. Monteleme civataları paket içeriğinde bulunuyor.
{% endhint %}

Yaklaşık ağırlıklar:

* [Kraken X60](../../motorlar/fircasiz-motorlar/kraken-x60.md) motorlu MK4n Swerve Modülü - 2,95 kg (Kodlayıcı, alt montaj plakası, montaj donanımı vb. dahildir).
* [NEO](../../motorlar/fircasiz-motorlar/neo-v1/) motorlu MK4n Saptırma Modülü - 2,72 kg (Kodlayıcı, alt montaj plakası, montaj donanımı vb. dahildir)
