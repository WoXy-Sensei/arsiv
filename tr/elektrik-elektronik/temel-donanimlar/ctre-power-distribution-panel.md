# CTRE Power Distribution Panel

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### **CTRE Power Distribution Panel (PDP)**

CTRE (Cross the Road Electronics) Power Distribution Panel (PDP), FRC robotlarında kullanılan bir güç dağıtım ünitesidir. Bu panel, robot üzerindeki motor kontrolörleri, sensörler ve diğer elektronik bileşenler için güvenilir bir güç kaynağı sağlar. PDP, robotun elektrik sistemini korur ve izler, böylece hem güvenlik hem de verimlilik sağlar.

#### **Temel Özellikler**

* **Güç Dağıtımı**: PDP, robotun ana aküsünden gelen gücü tüm bileşenlere dengeli bir şekilde dağıtır.
* **Devre Koruması**: PDP üzerindeki sigortalar, her bir bağlantı için aşırı akım koruması sağlar. Bu, robotun elektrik sisteminde kısa devre gibi tehlikeli durumları önler.
* **CAN Bus Entegrasyonu**: PDP, CAN bus üzerinden RoboRIO’ya bağlanır. Bu bağlantı ile akım ve voltaj gibi önemli veriler RoboRIO’ya iletilir ve robotun Driver Station’ı üzerinden izlenebilir.
* **LED Göstergeler**: PDP üzerinde her bir çıkış için LED göstergeler bulunur. Bu LED’ler, bağlantı durumunu ve olası hataları hızlı bir şekilde belirlemeye yardımcı olur.

#### **Bağlantı Noktaları**

* **Ana Güç Girişi (12V)**: Robot aküsünden gelen gücü alır ve robotun tüm bileşenlerine dağıtır.
* **Kanallar (Channels)**: PDP, toplamda 16 adet kanala sahiptir. Bu kanallar motor sürücüler, sensörler ve diğer bileşenler için güç çıkışları sağlar.
* **CAN Bus Bağlantısı**: PDP, CAN bus üzerinden motor kontrol üniteleri ve RoboRIO ile iletişim kurar.
* **Voltage Regulator Module (VRM)**: Ekstra voltaj regülasyonu için VRM bağlantı noktaları bulunur. Bu modüller, daha hassas bileşenler için sabit voltaj sağlar.

#### **CTRE Power Distribution Panel (PDP) Kanal Yapısı**

CTRE Power Distribution Panel (PDP), toplamda **16 adet çıkış kanalı** sunar. Bu kanalların dağılımı şu şekildedir:

* **8 adet 40A kanalı**

**40A Sigortalar**: 40A kanallarında kullanılan sigortalar, yüksek akım çeken motorlar ve cihazlar için tasarlanmıştır. CIM ve Mini CIM motorları gibi yüksek güç gereksinimi olan bileşenleri korur.

* **8 adet 30A kanalı**

**30A Sigortalar**: 30A kanallarında kullanılan sigortalar, daha düşük akım gereksinimleri olan motorlar ve cihazlar için uygundur.

{% hint style="info" %}
Eğer daha fazla çıkış ve farklı amperaj değerlerinde bir güç dağıtım ünitesi arıyorsanız, **Power Distribution Hub (PDH)** öneriyoruz.
{% endhint %}

