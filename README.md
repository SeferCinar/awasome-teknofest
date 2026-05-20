# awasome-teknofest# Awesome Teknofest [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Teknofest yarışmalarına hazırlanan takımlar, geliştiriciler ve meraklılar için derlenmiş kaynaklar.
> A curated list of resources for Teknofest competition teams, developers, and enthusiasts.

[Teknofest](https://www.teknofest.org), Türkiye'nin en büyük havacılık, uzay ve teknoloji festivali. İHA, İKA, İDA, model uydu, roket, su altı sistemleri, yapay zeka ve daha pek çok kategoride yüzlerce takım yarışıyor. Bu liste, takımların **sıfırdan başlarken** veya **bir sonraki seviyeye geçerken** ihtiyaç duyacağı her şeyi tek yerde topluyor: yarışma şartnameleri, açık kaynak yazılımlar, simülatörler, donanım rehberleri, eğitim materyalleri ve topluluklar.

## İçindekiler

- [Resmi Kaynaklar](#resmi-kaynaklar)
- [Yarışma Kategorileri](#yarışma-kategorileri)
  - [İnsansız Hava Araçları (İHA)](#i̇nsansız-hava-araçları-i̇ha)
  - [İnsansız Kara Aracı (İKA)](#i̇nsansız-kara-aracı-i̇ka)
  - [İnsansız Deniz / Su Altı Sistemleri (İDA / İSAS)](#i̇nsansız-deniz--su-altı-sistemleri-i̇da--i̇sas)
  - [Model Uydu](#model-uydu)
  - [Roket](#roket)
  - [Robotaksi & Otonom Araçlar](#robotaksi--otonom-araçlar)
  - [Yapay Zeka Yarışmaları](#yapay-zeka-yarışmaları)
  - [Diğer Kategoriler](#diğer-kategoriler)
- [Otopilot & Flight Stack](#otopilot--flight-stack)
- [ROS & Robotik Middleware](#ros--robotik-middleware)
- [Simülatörler](#simülatörler)
- [Yer İstasyonu Yazılımları](#yer-i̇stasyonu-yazılımları)
- [Bilgisayarlı Görü & Algılama](#bilgisayarlı-görü--algılama)
- [Donanım Rehberleri](#donanım-rehberleri)
- [Açık Kaynak Takım Depoları](#açık-kaynak-takım-depoları)
- [Eğitim Kaynakları](#eğitim-kaynakları)
- [Topluluklar](#topluluklar)
- [Katkıda Bulunma](#katkıda-bulunma)

---

## Resmi Kaynaklar

- [Teknofest Resmi Sitesi](https://www.teknofest.org) — Yarışma duyuruları, başvurular, takvim.
- [Teknofest Yarışmalar Sayfası](https://www.teknofest.org/tr/yarismalar/) — Tüm aktif yarışma kategorilerinin listesi.
- [Teknofest Finalist Takımlar](https://www.teknofest.org/tr/competitions/competition_report/) — Geçmiş yıllardaki finalist takımlar ve raporları.
- [T3 Vakfı](https://t3vakfi.org/) — Türkiye Teknoloji Takımı Vakfı, Teknofest'in yürütücü kuruluşu.
- [TEKNOFEST-YARISMALAR GitHub](https://github.com/TEKNOFEST-YARISMALAR) — Yarışmalar için resmi GitHub organizasyonu (örnek veri setleri, dökümanlar).

---

## Yarışma Kategorileri

> Teknofest 2025'te toplam **51 ana kategori ve 117+ alt kategori** vardı. Aşağıda yazılım/donanım ağırlıklı olanları topladık.

### İnsansız Hava Araçları (İHA)

- **Sabit Kanat İHA Yarışması** — Üniversite seviyesi, otonom uçuş + görev tabanlı.
- **Döner Kanat İHA Yarışması** — Multirotor platformlar üzerinde otonom görev.
- **Savaşan İHA** — Yüksek otonomi gerektiren hava-hava görev senaryoları.
- **Drone Şampiyonası** — FPV racing odaklı.
- **Sürü İHA Yarışması** — Çoklu drone koordinasyonu.

### İnsansız Kara Aracı (İKA)

- **İnsansız Kara Aracı Yarışması** — 2025'te ilk kez düzenlendi, otonom kara aracı yarışı.
- **Tarımsal İKA Yarışması** — Tarım otomasyonu odaklı.

### İnsansız Deniz / Su Altı Sistemleri (İDA / İSAS)

- **İnsansız Su Altı Sistemleri Yarışması** — ROV/AUV görev tabanlı yarışma.
- **İnsansız Deniz Aracı** — Yüzey araçları için otonom navigasyon.

### Model Uydu

- **Model Uydu Yarışması** — CanSat tarzı, atmosferik veri toplama + iniş kontrolü.

### Roket

- **Roket Yarışması** — Hedef irtifa + faydalı yük kurtarma.
- **Dikey İnişli Roket Yarışması** — Reusable rocket konsepti.
- **Su Altı Roket Yarışması** — 2025'te ilk kez düzenlendi.

### Robotaksi & Otonom Araçlar

- **Robotaksi - Binek Otonom Araç Yarışması** — Şehir içi otonom sürüş senaryoları.
- **Karma Sürü Simülasyon Yarışması** — Çoklu otonom araç simülasyonu.

### Yapay Zeka Yarışmaları

- **Havacılıkta Yapay Zeka Yarışması** — Hava görüntülerinde nesne tespiti vb.
- **Ulaşımda Yapay Zeka Yarışması** — Trafik ve ulaşım problemleri.
- **Sağlıkta Yapay Zeka Yarışması** — Tıbbi görüntü analizi, tanı destek sistemleri.
- **Türkçe Doğal Dil İşleme Yarışması (acikhack)** — Türkçe NLP odaklı.

### Diğer Kategoriler

- **Blokzincir Yarışması** — Blockchain tabanlı çözümler.
- **Engelsiz Yaşam Teknolojileri** — Erişilebilirlik odaklı.
- **Biyoteknoloji İnovasyon Yarışması**
- **Çevre ve Enerji Teknolojileri**
- **Tarım Teknolojileri**

---

## Otopilot & Flight Stack

Hava ve kara araçları için en yaygın açık kaynak otopilot yazılımları.

- [ArduPilot](https://github.com/ArduPilot/ardupilot) — Açık kaynak otopilot. Copter, Plane, Rover, Sub ve Tracker desteği.
- [ArduPilot Dev Docs](https://ardupilot.org/dev/) — Geliştirici dökümantasyonu, ROS entegrasyonu dahil.
- [PX4-Autopilot](https://github.com/PX4/PX4-Autopilot) — Drone, VTOL, rover ve daha fazlası için açık kaynak otopilot stack.
- [PX4 User & Dev Guide](https://docs.px4.io/) — PX4 resmi rehberi.
- [MAVLink](https://mavlink.io/) — Drone ile yer istasyonu arasındaki standart haberleşme protokolü.
- [DroneCAN](https://dronecan.github.io/) — Havacılık ve robotik için CAN bus tabanlı haberleşme.

---

## ROS & Robotik Middleware

- [ROS 2 Documentation](https://docs.ros.org/) — Resmi ROS 2 rehberi.
- [ROS 2 Humble](https://docs.ros.org/en/humble/) — Şu an için PX4 ve ArduPilot tarafından önerilen LTS sürüm.
- [PX4 ROS 2 User Guide](https://docs.px4.io/main/en/ros2/user_guide.html) — PX4-ROS 2 entegrasyonu.
- [ArduPilot ROS 2](https://ardupilot.org/dev/docs/ros2.html) — ArduPilot-ROS 2 entegrasyonu.
- [MAVROS](https://github.com/mavlink/mavros) — MAVLink↔ROS köprüsü.
- [px4_ros_com](https://github.com/PX4/px4_ros_com) — PX4 için ROS 2 örnekleri ve yardımcı kodlar.
- [px4_msgs](https://github.com/PX4/px4_msgs) — PX4 ROS 2 mesaj tanımları.

---

## Simülatörler

- [Gazebo](https://gazebosim.org/) — Robotik için en yaygın simülatör. PX4 ve ArduPilot ile entegre.
- [jMAVSim](https://github.com/PX4/jMAVSim) — PX4 için hafif drone simülatörü.
- [AirSim](https://github.com/microsoft/AirSim) — Microsoft'un fotogerçekçi drone/araç simülatörü (arşivlendi ama hâlâ kullanılıyor).
- [CARLA](https://carla.org/) — Otonom sürüş simülatörü, Robotaksi için ideal.
- [Webots](https://cyberbotics.com/) — Açık kaynak çok amaçlı robotik simülatörü.

---

## Yer İstasyonu Yazılımları

- [QGroundControl](https://qgroundcontrol.com/) — Cross-platform, PX4 & ArduPilot uyumlu.
- [Mission Planner](https://ardupilot.org/planner/) — ArduPilot'un resmi yer istasyonu (Windows).
- [APM Planner 2](https://ardupilot.org/planner2/) — Cross-platform ArduPilot yer istasyonu.
- [MAVProxy](https://github.com/ArduPilot/MAVProxy) — Komut satırı tabanlı, scriptable yer istasyonu.

---

## Bilgisayarlı Görü & Algılama

- [OpenCV](https://opencv.org/) — Klasik bilgisayarlı görü kütüphanesi, neredeyse her İHA/İKA görevinde kullanılır.
- [YOLO (Ultralytics)](https://github.com/ultralytics/ultralytics) — Gerçek zamanlı nesne tespiti, Teknofest yarışmalarında en yaygın model.
- [MediaPipe](https://github.com/google/mediapipe) — Hafif ML çözümleri (poz, el, yüz tespiti).
- [OpenMMLab](https://github.com/open-mmlab) — MMDetection, MMSegmentation ve diğer state-of-the-art CV araçları.

---

## Donanım Rehberleri

- [Pixhawk Resmi](https://pixhawk.org/) — Standart otopilot donanımı.
- [NVIDIA Jetson](https://developer.nvidia.com/embedded-computing) — On-board AI için en yaygın companion computer ailesi.
- [Raspberry Pi](https://www.raspberrypi.com/) — Düşük maliyetli companion computer / yer istasyonu.

> Bu bölüm sensör seçimi, motor/ESC, batarya, telemetri ve PDB gibi konularda genişlemeye açık. Katkı bekleniyor!

---

## Açık Kaynak Takım Depoları

> Geçmiş Teknofest takımlarının paylaştığı açık kaynak projeler. Şartname incelemek, mimari fikir almak ve kod örneği görmek için altın değerinde.

- [GitHub `teknofest` topic](https://github.com/topics/teknofest) — Tüm teknofest etiketli repoların listesi.
- [GitHub `teknofest2024` topic](https://github.com/topics/teknofest2024) — 2024 yarışmalarına özel repolar.
- [GitHub `teknofest2023` topic](https://github.com/topics/teknofest2023) — 2023 yarışmalarına özel repolar.
- [BeeRocketry Ground Station](https://github.com/topics/teknofest) — Roket için PyQt6 yer istasyonu (topic içinde aranabilir).
- [KOU Rover AGV UI](https://github.com/topics/teknofest) — ROS 2 + PyQt6 tabanlı otonom AGV arayüzü.

> Buraya kendi/takımınızın repo'sunu eklemek için PR açın!

---

## Eğitim Kaynakları

### Türkçe

> Buraya katkı sağlamak için PR açın 

### İngilizce

- [PX4 Developer Guide](https://docs.px4.io/main/en/development/development.html) — PX4 ile geliştirme yapmaya başlangıç.
- [ArduPilot Wiki](https://ardupilot.org/ardupilot/) — Tüm ArduPilot dökümantasyonu.
- [ROS 2 Tutorials](https://docs.ros.org/en/humble/Tutorials.html) — Resmi ROS 2 eğitim serisi.
- [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) — Robotik algoritmalarının Python ile sıfırdan implementasyonu (path planning, SLAM, control). **Mutlaka inceleyin.**

---

## Topluluklar

- [Dronecode Discord](https://discord.gg/dronecode) — PX4 ve ilgili projelerin resmi Discord'u.
- [ArduPilot Discord](https://discord.gg/ArduPilot) — ArduPilot resmi Discord'u.
- [ROS Discourse](https://discourse.ros.org/) — ROS topluluğunun resmi forumu.
- [Dronecode Forum](https://discuss.px4.io/) — PX4 ve drone geliştirme forumu.

> Türkiye merkezli Discord/Telegram grupları için PR açın!

---

## Katkıda Bulunma

Katkı için [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını okuyun. Kısa özet:

1. Eklemek istediğiniz kaynak **açıkça Teknofest takımlarına faydalı** olmalı.
2. Format: `- [İsim](link) — Türkçe veya İngilizce kısa açıklama, nokta ile biter.`
3. Linkler aktif olmalı, ölü linkler kabul edilmez.
4. Reklam / spam içerikler ve "kişisel CV / portfolio" tarzı linkler kabul edilmez.
5. Bir kategoride alfabetik / kronolojik sıralamayı koruyun.

[awesome.re kılavuzu](https://github.com/sindresorhus/awesome/blob/main/awesome.md) baz alınmıştır.

---

## Lisans

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Bu çalışma [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) ile kamuya açıktır.
