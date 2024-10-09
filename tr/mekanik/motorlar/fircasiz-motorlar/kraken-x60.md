# Kraken x60

**Kraken X60 Motor**, FRC (FIRST Robotics Competition) yarışmalarında kullanılan yüksek performanslı bir fırçasız DC motorudur. Bu motor, özellikle zorlu uygulamalarda enerji verimliliği, dayanıklılık ve yüksek güç sunmasıyla dikkat çeker.

***

<figure><img src="../../../.gitbook/assets/image (15) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

***

## Özellikleri:

| Parametre                  | Değer      | Birim                |
| -------------------------- | ---------- | -------------------- |
| Serbest Hız                | 6.000      | Devir/dakika         |
| Serbest Akım               | 2          | A                    |
| Durma Torku                | 7.09       | Nm                   |
| Duraklama Akımı            | 366        | A                    |
| Maksimum Güç               | 1.108      | B                    |
| Maksimum Verimlilik        | %87        | W(dışarı) / W(içeri) |
| Akım @ Maksimum Verimlilik | 30         | A                    |
| Güç @ 40A                  | 413(86.1%) | W(%Etki)             |
| Güç @ 30A                  | 313(87.1%) | W(%Etki)             |
| Güç @ 20A                  | 207(86%)   | W(%Etki)             |
| Güç @ 10A                  | 94(78%)    | W(%Etki)             |

***

## Dahili Kontrolcünün Avantajları

{% hint style="info" %}
Entegre bir motor kontrolcüsü, kontrolcü ve motor arasındaki kablolamayı üstlenir, bu da ekiplerin endişelenmesi gereken bir kablo hattı daha azaltır.

Kontrolcü motorun içine yerleştirildiğinden, ekiplerin bağımsız motor kontrolörlerini monte etmek için robotlarında yer ayırmaları gerekmez.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (24) (1).png" alt=""><figcaption></figcaption></figure>

***

## Durum Işıkları

<figure><img src="../../../.gitbook/assets/image (26) (1).png" alt="" width="563"><figcaption></figcaption></figure>

| LED Durumu               | Tanım                                                                                        |
| ------------------------ | -------------------------------------------------------------------------------------------- |
| Kapalı/Turuncu dönüşümlü | Talon FX devre dışı. Robot kontrolörü veriyolunda eksik veya tanılama sunucusu kurulu değil. |
| Eşzamanlı Kapalı/Turuncu | Talon FX devre dışı. Phoenix Robot Controller'da çalışıyor.                                  |
| Kırmızı/Yeşil dönüşümlü  | Talon FX lisanslı değil. Lütfen Phoenix Tuner'da cihazı lisanslayın.                         |
| Kapalı/Yavaş Kırmızı     | CAN/PWM algılanmadı.                                                                         |
| Kırmızı/Turuncu          | Hasarlı Donanım                                                                              |
| Kapalı/Kırmızı           | Limit Switch veya Soft Limit tetiklendi.                                                     |
| Yeşil/Turuncu            | Cihaz önyükleyicide.                                                                         |

***

### Avantajları şunlardır:

* **Enerji Verimliliği**: Fırçasız motor teknolojisi sayesinde daha az enerji tüketir ve uzun ömür sunar.
* **Az Bakım Gereksinimi**: Fırçasız yapısı, aşınmayı ve yıpranmayı azaltarak bakım ihtiyacını minimuma indirir.
* **Kompakt Tasarım**: Hafif ve kompakt yapısı, robot tasarımında esneklik sağlar ve yer tasarrufu sağlar.

### Dezavantajlar şunlardır:

* **Yüksek Maliyet**: Fırçasız motorlar genellikle daha pahalıdır, bu da bütçesi kısıtlı takımlar için dezavantaj oluşturabilir.

***

Kraken X60 motor, yüksek tork ve hız gerektiren uygulamalarda mükemmel bir seçimdir. Yüksek performans ve verimlilik arayan FRC takımları için ideal bir çözümdür.
