# NI roboRIO

<div align="left">

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

</div>

### 1. **RoboRIO'nun Tanımı ve İşlevi**

* **Tanım**: RoboRIO, National Instruments tarafından geliştirilen, FRC robotlarını kontrol eden güçlü bir endüstriyel kontrolör. Gömülü bir Linux işletim sistemine sahip ve robotun çeşitli bileşenlerini yönetir.
* **İşlevler**:
  * Robotun motorlarını, sensörlerini, ve diğer elektronik bileşenlerini kontrol eder.
  * CAN, PWM, DIO (Dijital Giriş/Çıkış), USB ve Ethernet gibi birçok arabirim üzerinden bağlantı sağlar.

### 2. **RoboRIO Bağlantı Noktaları**

#### **Power (Güç Bağlantısı):**

* **12V Giriş**: RoboRIO, FRC robot aküsünden gelen 12V gücü kullanır. Güç, Power Distribution Panel (PDP) veya Power Distribution Hub (PDH) aracılığıyla sağlanır. RoboRIO'nun üzerindeki güç göstergesi, bağlantının doğru olduğunu ve cihazın düzgün çalıştığını doğrular.

#### **PWM (Pulse Width Modulation) Portları:**

* **PWM Portları**: Bu portlar, motor sürücülerini (motor controller) veya servo motorları kontrol etmek için kullanılır. Her port bir motorun hızını veya pozisyonunu kontrol edebilir. RoboRIO’da birden fazla PWM portu bulunur ve her biri ayrı bir motoru ya da servoyu kontrol etmek için atanabilir.

#### **DIO (Dijital Giriş/Çıkış) Portları:**

* **DIO Portları (3 Pin)**: RoboRIO'da dijital sensörleri veya düğmeleri bağlamak için kullanılan portlardır. Her bir DIO portu 3 pinli bir yapıya sahiptir:
  * **5V (Besleme)**: Sensörlerin veya bileşenlerin güç alması için kullanılır.
  * **GND (Topraklama)**: Sistemin topraklama hattı, devrelerin güvenli çalışmasını sağlar.
  * **Sinyal (I/O)**: Dijital sinyallerin gönderildiği veya alındığı pindir. Giriş (input) modunda sensörlerden bilgi alınabilir, çıkış (output) modunda ise sinyaller gönderilerek belirli işlemler başlatılabilir.

{% hint style="info" %}
Bu portlar genellikle limit anahtarları, dijital sensörler, butonlar, LED'ler gibi cihazları bağlamak için kullanılır.
{% endhint %}

#### **Analog Giriş Portları:**

* **Analog Giriş (Analog Input) Portları**: Bu portlar, voltaj seviyelerine duyarlı analog sensörleri bağlamak için kullanılır. Örneğin, bir potansiyometre veya bir basınç sensörü gibi analog verileri ölçen cihazlar bu portlara bağlanabilir. RoboRIO, gelen voltajı okuyarak sensörlerden gelen verileri işler.

#### **CAN Bus:**

* **CAN (Controller Area Network) Bus**: CAN bus, motor sürücüleri ve sensörler gibi cihazlarla iletişim sağlar. CAN bus'ın avantajı, birçok cihazın aynı hat üzerinden kontrol edilmesini ve durumlarının izlenmesini sağlamasıdır. Bu portlar, özellikle robotun motor kontrol sistemlerinde yaygın olarak kullanılır.

#### **Röle (Relay) Bağlantıları:**

* **Röle Portları**: RoboRIO üzerindeki röle bağlantıları, kompresörler veya basit motorlar gibi cihazları kontrol etmek için kullanılır. Röle portları on/off sinyallerini kullanarak bileşenlerin açılıp kapatılmasını sağlar.

#### **USB ve Ethernet:**

* **USB Portları**: RoboRIO’da iki adet USB portu bulunur. Bu portlar, robot üzerinde kullanılan cihazları bağlamak için kullanılır. Özellikle:
  * **Kamera Bağlantısı**: USB portları, robot üzerindeki kameraların (örneğin USB kameralar) RoboRIO'ya bağlanması için kullanılabilir. Kameralardan gelen görüntüler Driver Station'a aktarılır, böylece sürücü robotu kontrol ederken kameradan canlı görüntü alabilir.
* **Ethernet**: RoboRIO’nun Ethernet portu, robotun programlanması ve kontrolü için kullanılır. Robotun ana bilgisayara (Driver Station) bağlanmasını sağlar. Ethernet bağlantısı, kablolu iletişim üzerinden hızlı ve güvenilir veri aktarımı sağlar.

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
**Dikkat: RoboRIO 1 Satıştan Kaldırıldı!**

RoboRIO kontrol cihazı iki nesil olarak sunulmuştur: **RoboRIO 1** ve **RoboRIO 2**. **RoboRIO 1** artık satışta değildir ve çeşitli sorunları nedeniyle kullanımı önerilmemektedir. Bu sorunlar arasında güç yönetimi, dayanıklılık ve performans ile ilgili bazı eksiklikler yer almaktadır.

Bu problemlerin giderilmesi ve daha güvenilir bir çözüm sunulması amacıyla **RoboRIO 2** piyasaya sürülmüştür. RoboRIO 2, daha gelişmiş donanım ve yazılım özelliklerine sahip olup, FRC robotları için tavsiye edilen cihazdır.
{% endhint %}

