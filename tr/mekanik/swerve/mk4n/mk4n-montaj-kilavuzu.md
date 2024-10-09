# MK4n Montaj Kılavuzu

## Swerve Modül Konfigürasyonları

Swerve modülü aşağıdaki gibi yapılandırılabilir:

* **Motor Tipi:** [Falcon 500](../../motorlar/fircasiz-motorlar/falcon-500.md), [Kraken X60](../../motorlar/fircasiz-motorlar/kraken-x60.md), [NEO](../../motorlar/fircasiz-motorlar/neo-v1/) veya [NEO Vortex](../../motorlar/fircasiz-motorlar/neo-v1/neo-vortex.md)
* **Dişli Oranı:** L1+, L2+ veya L3+
* **Tekerlek Tipi:** Kütük veya Colson
* **Direksiyon Enkoder Tipi:** 0,25“ Mıknatıs (CTRE CANcoder veya eşdeğeri) veya 0,5” Hex (REV Through Bore Kodlayıcı veya eşdeğeri)
* **Düzen:** A veya B

{% hint style="warning" %}
Lütfen unutmayın:

* Motor Tipi, pinyon dişlileri ve şaft ara parçaları gibi kit içinde sağlanan motora özgü bileşenleri ifade eder. Motorlar saptırma modülü kitine dahil değildir.
* Direksiyon Enkoder Tipi, Orta Kolon gibi kitte sağlanan direksiyon enkodere özel bileşenleri ifade eder. Kodlayıcı, saptırma modülü kitine dahil değildir.
* Swerve modül kiti, sipariş edildiğinde seçilen konfigürasyonlarla birlikte gelir. Kit, tüm konfigürasyonlar için tüm bileşenleri içermez.
{% endhint %}

***

## Montaj Kılavuzu Kuralları

Bu montaj kılavuzu tüm konfigürasyonların montajını detaylandırmaktadır, ancak aşağıdaki konfigürasyon önceliklidir örnekleme amacıyla kullanılmıştır:

* Motor Tipi: Kraken X60
* Dişli Oranı: L2+
* Tekerlek Tipi: Kütük
* Enkoder Tipi: 0.25” Mıknatıs
* Düzen: A

{% hint style="danger" %}
Özel önem taşıyan ayrıntılar ÖNEMLİ ile belirtilmiştir. Bunlara uyulmaması, saptırma modülünün çalışmasını önemli ölçüde etkileyebilir.
{% endhint %}

***

## İhtiyaç duyulan malzemeler

* 3/32“ altıgen anahtar (0,25” mıknatıslı enkoder ile kullanılan enkoder koruma vidaları için)
* 1/8” altıgen anahtar (#10 düğme başlı vidalar için)
* 5/32” altıgen anahtar (#10 soket başlı vidalar için)
* 3/16“ altıgen anahtar (1/4” soket başlı vidalar için)
* \#1 numaralı yıldız tornavida (CTRE CANcoder veya eşdeğerinin gövde vidaları için)

### Diş Kilitleyici ve Tutucu Bileşik

* Henkel Loctite 243 Diş Kilitleyici veya eşdeğeri
* 0,25” mıknatıslı direksiyon enkoderleri için (CTRE CANcoder veya eşdeğeri): Henkel Loctite 609 Tespit Bileşeni veya eşdeğeri

#### Diş Kilitleyici Kullanımı:

{% hint style="warning" %}
ÖNEMLİ: Direksiyon enkoderini sabitlemek için kullanılan vidalar hariç tüm vidaları sabitlemek için Henkel Loctite 243 Diş Kilitleyici veya eşdeğerini kullanın, çünkü enkoder muhafazası ile olumsuz reaksiyona girebilir.
{% endhint %}

#### Yağlama:

{% hint style="warning" %}
ÖNEMLİ Tüm dişlileri Lucas White Lithium, Lucas Red “N” Tacky veya eşdeğer bir gres ile yağlayın Swerve modülünü kullanmadan ÖNCE ve kullandıkça DÜZENLİ olarak.
{% endhint %}

### Swerve Modül Düzeni

MK4n Swerve Modülü simetrik bir ayak izine sahip değildir, bu nedenle “A” ve “B” olarak bilinen yansıtılmış düzenlerde mevcuttur. Tipik bir tahrik tabanı iki A düzenine ve iki B düzenine sahip olacaktır:

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

B düzeni için montaj işlemi aynıdır, ancak:

* Bileşenlerin düzeni genellikle yansıtılır.
* Aşağıdaki bileşenler düzen A ve B arasında farklılık gösterir:&#x20;
* Ana Plaka ve Motor Plakası

İki saptırma modülü düzenine özgü bileşenler işaretlerinden tanımlanabilir:

<figure><img src="../../../.gitbook/assets/image (3).png" alt="" width="563"><figcaption></figcaption></figure>

***

## Adım 1: Orta Kolonun Hazırlanması

Bu adım sadece 0,25” mıknatıs kullanan bir direksiyon enkoderi (CTRE CANcoder veya eşdeğeri) kullanılıyorsa geçerlidir.

Mıknatısı Orta Kolona bağlayın:

1. Mıknatısa Loctite 609 veya eşdeğerini uygulayın.
2. Mıknatısı Orta Kolondaki 0,25 inçlik deliğe tamamen yerleştirin.

{% hint style="info" %}
Lütfen mıknatısın kodlayıcıya dahil olduğunu ve saptırma modülü kitine dahil olmadığını unutmayın.
{% endhint %}

{% hint style="danger" %}
ÖNEMLİ:

* Mıknatısın Orta Kolonun üst kısmıyla aynı hizada olduğundan emin olun.
* Mıknatıs ve Orta Kolon üzerindeki fazla tutucu bileşeni silin.
* Mıknatısı yerine yapıştırmak için siyanoakrilat yapıştırıcı (“Süper Yapıştırıcı”) kullanmayın. Çok kısa bir çalışma süresi vardır ve mıknatıs Orta Kolona tam olarak yerleştirilmeden önce yerine yapışabilir.
* Orta Kolon alt tertibatını mıknatıs yukarı bakacak şekilde bir kenara koyun, böylece tutucu bileşik mıknatıs istemeden kaymadan sertleşebilir.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

***

## Adım 2: Direksiyon Yatağının Takılması

* Büyük Direksiyon Yatağını Ana Plakaya takın ve ardından beş adet #10-32 x 0,25” Düğme Başlı Vida ile sabitleyin.

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Ana Plaka çok sayıda dişli deliğe sahip olduğundan, rulmanı sabitlemek için doğru beş deliğin kullanıldığından emin olun.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

***

## Adım 3: Yardımcı Motor Desteği Montajı

* Ofset Motor Plakası Bağlantısını #10-32 x 1“ Soket Başlı Vida ile 0,313” OD x 0,625” Uzun Ayırma ile gevşek bir şekilde sabitleyin.&#x20;
* Vidanın son hizalanması ve sıkılması 14. Adımda motorlar takılırken gerçekleşecektir.

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

***

## Adım 4: Ara Mil Montajı

* 6802ZZ Rulmanı (24 mm dış çap) Taban Kasnağına ve ardından Ara Mili bu Rulmana yerleştirin.
* Ardından, küçük 0,375” Altıgen Delikli Dişliyi Ara Mil üzerine takın ve ardından e-klipsi Ara Mil üzerindeki oluğa geçirerek sabitleyin.

{% hint style="danger" %}
ÖNEMLİ E-klipsin oluğa tam olarak oturduğundan emin olun.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Bu dişlinin boyutu, saptırma modülünün yapılandırıldığı dişli oranına bağlıdır:
{% endhint %}

<div align="center">

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

</div>

***

## Adım 5: Orta Kolon Montajı

Saptırma modülünün yönlendirme ekseni, 0,25“ mıknatıslı enkoderler (CTRE CANcoder veya eşdeğeri) için bir Orta Sütun veya 0,5” altıgen enkoderler (REV Through Bore Encoder veya eşdeğeri) için bir Orta Sütun ile yapılandırılabilir.

### 0,25” Mıknatıslı Kodlayıcı Yapılandırması

* Çift Dişliye iki adet 6802ZZ Rulman (24 mm Dış Çap) yerleştirin ve ardından bu parçaları 1/4“-20 x 0,625” Soket Başlı Vida ile sabitlenmiş Orta Kolon ile yakalayın.

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

### 0.5” Hex Encoder Configuration

* İki adet 6802ZZ Rulmanı (24 mm Dış Çap) Çift Dişliye yerleştirin ve ardından 1/4“-20 x 0,625” Soket Başlı Vida ile sabitlenmiş Orta Kolon ile yakalayın.

<figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

Çift Dişlinin boyutu, saptırma modülünün yapılandırıldığı dişli oranına bağlıdır:

<figure><img src="../../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

***

## Adım 6: Taban Kasnağının Takılması

* R188ZZ Rulmanı (0,5” Dış Çap) Ana Plakaya yerleştirin.

<figure><img src="../../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

* Direksiyon Kayışını Direksiyon Mili ve Taban Kasnağının etrafına yerleştirin ve ardından Taban Kasnağını büyük yatağa ve Direksiyon Milini küçük yatağa toplu olarak yerleştirin.

<figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Taban Kasnağının alt kısmı büyük yatağın alt kısmı ile aynı hizada olmalıdır.
{% endhint %}

***

## Adım 7: Alt Tahrik Grubu

* 15T Konik Dişliyi Ara Milin üzerine yerleştirin
* Ardından 1mm Kalınlığında Şimi ve ardından 688ZZ Rulmanı (16mm Dış Çap) yerleştirin.

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

* Tekerlek Bağlantısı B'yi iki adet 1/4“-20 x 0,625” Soket Başlı Vida ile Taban Kasnağına takın.

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

***

## Adım 8: Üst Dişlinin Takılması

* **Direksiyon Mili için:** Direksiyon Miline 50T dişli yerleştirin, ardından 0,5” Uzun Ara Parçayı ve 688ZZ Rulmanı (16mm OD) yerleştirin.
* Avara Mili için: Ana Plakaya bir 688ZZ Rulman (16 mm Dış Çap) yerleştirin. Ardından, Avara Miline bir 50T Dişli ve ardından bir 688ZZ Rulman (16mm OD) yerleştirin.
* Orta Kolon üzerine bir 6802ZZ Rulman (24 mm Dış Çap) yerleştirin.

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

***

## Adım 9: Motor Plakası Montajı

* Motor Plakasını üç Rulmanın üzerine yerleştirin ve üç rulman deliğine tam olarak oturduklarından emin olun.

<figure><img src="../../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

* Motor Plakasını üç adet #10-32 x 2,25“ Soket Başlı Vida ile üç adet #10 ID x 1,875” Uzun Paspayı üzerinden sabitleyin.

<figure><img src="../../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

***

## Adım 10: Tekerlek Alt Montajı

Saptırma modülü bir Kütük Tekerlek veya Colson Tekerlek ile yapılandırılabilir.

### Kütük Teker

* 45T Konik Dişliyi altı adet #10-32 x 0,75” Düğme Başlı Vida ile Tekerleğe sabitleyin.
* Konik Dişli tarafına R8ZZ Yatağı (1,125“ dış çap) ve Tekerlek Ara Parçasını yerleştirin ve karşı tarafa R6ZZ Yatağı (0,875” dış çap) yerleştirin.

<figure><img src="../../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

### Colson Teker

* 45T Konik Dişliyi üç adet #10-32 x 1” Soket Başlı Vida ile Tekerleğe sabitleyin.&#x20;
* Konik Dişli tarafına R8ZZ Yatağı (1,125“ dış çap) ve Tekerlek Ara Parçasını yerleştirin ve karşı tarafa R6ZZ Yatağı (0,875” dış çap) yerleştirin.

<figure><img src="../../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

***

## Adım 11: Tekerlek Montajı

* Omuz Cıvatasını kısmen Tekerlek Bağlantısı A'dan ve Tekerlek Ara Parçasından geçirin.

<figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

* Tekerlek alt grubunu, Tekerlek Bağlantısı A'yı iki adet 1/4“-20 x 1” Soket Başlı Vida ile Taban Kasnağına ve Omuz Cıvatasını Tekerlek Bağlantısı B'ye sabitleyerek saptırma modülüne takın.

<figure><img src="../../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

***

## Adım 12: Kodlayıcı Kurulumu

Saptırma modülünün yönlendirme ekseni, 0,25“ mıknatıslı kodlayıcı (CTRE CANcoder veya eşdeğeri) veya 0,5” altıgen kodlayıcı (REV Through Bore Encoder veya eşdeğeri) ile çalışacak şekilde yapılandırılabilir.

### 0,25” Mıknatıslı Kodlayıcı

* Kodlayıcı muhafazasının tabanını, kodlayıcı ile birlikte verilen iki adet #3-48 vida ile Motor Plakasına sabitleyin.

{% hint style="danger" %}
ÖNEMLİ Muhafazaya zarar verebileceğinden bu vidalarda diş kilitleyici kullanmayın.
{% endhint %}

* Devre kartını ve enkoder muhafazasının kapağını enkoder ile birlikte verilen #2-28 vida ile enkoder muhafazasının tabanına sabitleyin.

{% hint style="danger" %}
ÖNEMLİ Bu vida üzerinde diş kilitleyici kullanmayın, aksi takdirde muhafazaya zarar verebilir.
{% endhint %}

{% hint style="danger" %}
ÖNEMLİ Muhafazaya zarar verebileceğinden bu vidayı aşırı sıkmayın.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

* Enkoder Korumasını üç adet #8-32 x 0,875“ Düğme Başlı Vida ve üç adet #8 ID x 0,531” Uzun Ara Parça kullanarak monte edin.

<figure><img src="../../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

### 0,5” Altıgen Kodlayıcı

* Enkoderin altıgen deliğini Orta Kolonun eşleşme yüzeyleriyle hizalayın ve ardından enkoderi iki adet #10-32 x 0,5” Düğme Başlı Vida ile monte edin.

{% hint style="danger" %}
ÖNEMLİ Muhafazaya zarar verebileceğinden bu vidaları aşırı sıkmayın.
{% endhint %}

{% hint style="info" %}
Kodlayıcı Koruması ve 0,25“ mıknatıslı kodlayıcı kurulum işleminde (Adım 12'nin başlarında) ayrıntılı olarak açıklanan üç vida ve ara parçası 0,5” altıgen kodlayıcı ile kullanılmaz.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

***

## Adım 13: Motor Alt Montajı

Saptırma modülü, eşleşen bir çift Falcon 500, Kraken X60, NEO veya NEO Vortex motorla çalışacak şekilde yapılandırılabilir. Saptırma modülü, eşleşmeyen motorlarla (örneğin bir Kraken X60 tahrik motoru ve Falcon 500 direksiyon motoru) çalışabilir, ancak bu düzenleme için ek parçalar gerekebilir.

### [Falcon 500 ](../../motorlar/fircasiz-motorlar/falcon-500.md)

{% hint style="info" %}
Falcon 500 motorları ile birlikte verilen motor mili ara parçalarını kullanın.
{% endhint %}

#### Tahrik Motoru:

Aşağıdakileri sırayla motor miline takın:&#x20;

* 0,25“ Uzun Ara Parçası, 0,125” Uzun Ara Parçası, 16T Pinyon Dişlisi, 0,25” Uzun Ara Parçası, 0,063” Uzun Ara Parçası. Bu parçaları #8-32 x 0,5” Makas Başlı Vida ile sabitleyin.

{% hint style="danger" %}
ÖNEMLİ Bu vida üzerinde diş kilitleyici kullanıldığından emin olun.
{% endhint %}

#### Rotasyon Motoru:

Aşağıdakileri sırayla motor miline takın:&#x20;

* 16T Pinyon Dişlisi, 0,25“ Uzun Ara Parça, 0,25” Uzun Ara Parça, 0,125” Uzun Ara Parça, 0,063” Uzun Ara Parçası. Bu parçaları #8-32 x 0,5” Makas Başlı Vida ile sabitleyin.

{% hint style="danger" %}
ÖNEMLİ Bu vida üzerinde diş kilitleyici kullanıldığından emin olun.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

### [Kraken X60](../../motorlar/fircasiz-motorlar/kraken-x60.md)

Tahrik Motoru:

* Aşağıdakileri sırayla motor miline takın:&#x20;
* 0,125“ Uzun Ara Parçası, 16T Pinyon Dişlisi, 0,375” Uzun Ara Parçası. Bu parçaları #10-32 x 0,5” Düğme Başlı Vida ile sabitleyin.

{% hint style="danger" %}
ÖNEMLİ Bu vida üzerinde diş kilitleyici kullanıldığından emin olun.
{% endhint %}

Rotasyon Motoru:

* Aşağıdakileri sırayla motor miline takın:&#x20;
* 16T Pinyon Dişlisi, 0,125“ Uzun Ara Parçası, 0,375” Uzun Ara Parçası. Bu parçaları #10-32 x 0,5” Düğme Başlı Vida ile sabitleyin.

{% hint style="danger" %}
ÖNEMLİ Bu vida üzerinde diş kilitleyici kullanıldığından emin olun.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### [Neo](../../motorlar/fircasiz-motorlar/neo-v1/)

#### Tahrik Motoru:

* Aşağıdakileri sırayla motor miline takın:&#x20;
* 0,438” Uzun Ara Parçası, 2mm Makine Anahtarı, 16T Pinyon Dişlisi.

#### Rotasyon Motoru:

* Aşağıdakileri sırayla motor miline takın:&#x20;
* 1mm Kalın Şim, 2mm Makine Anahtarı, 16T Pinyon Dişlisi. Bu parçaları 8mm ID Tutma Halkası ile sabitleyin.

<figure><img src="../../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

### [Neo Vortex](../../motorlar/fircasiz-motorlar/neo-v1/neo-vortex.md) (8mm Anahtarlı Mil)

#### Tahrik Motoru:

* Aşağıdakileri sırayla motor miline takın:&#x20;
* 0,438” Uzunluğunda Ara Parçası, 2mm Makine Anahtarı, 16T Pinyon Dişlisi. Bu parçaları 8mm ID Tespit Halkası ile sabitleyin.

#### Rotasyon Motoru:

* Aşağıdakileri sırayla motor miline takın:&#x20;
* 1mm Kalın Şim, 2mm Makine Anahtarı, 16T Pinyon Dişlisi. Bu parçaları 8mm ID Tespit Halkası ile sabitleyin.

<figure><img src="../../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

***

## Adım 14: Motor Kurulumu

* Çift Ara Parçayı, iki deliğini aşağıdaki Ofset Motor Plakası Bağlantısı ve yukarıdaki Motor Plakası ile hizalayarak yerleştirin.

<figure><img src="../../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

#### [Falcon 500](../../motorlar/fircasiz-motorlar/falcon-500.md)

<figure><img src="../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

#### [Kraken x60](../../motorlar/fircasiz-motorlar/kraken-x60.md)

<figure><img src="../../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

#### [Neo](../../motorlar/fircasiz-motorlar/neo-v1/)&#x20;

<figure><img src="../../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

#### [Neo Vortex](../../motorlar/fircasiz-motorlar/neo-v1/neo-vortex.md)

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
ÖNEMLİ Her iki motoru da taktıktan sonra, Adım 3'te gevşek bir şekilde takılmış olan Yardımcı Motor Destek Vidasını sıkın. Gerekirse yeniden diş kilitleyici uygulayın.
{% endhint %}

***

## Adım 15: Swerve Modül Kurulumu

* 10 ID x 1,875“ Uzunluğundaki Ara Parçayı Ana Plaka ve Alt Plaka arasına #10-32 x 2,25” Soket Başlı Vida ile sabitleyin.
* Saptırma modülü, altı adet #10-32 x 2,5“ Soket Başlı Vida ile 2” x 1” dikdörtgen boruya monte edilir.

<figure><img src="../../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>
