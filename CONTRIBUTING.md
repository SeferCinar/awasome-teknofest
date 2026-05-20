# Katkıda Bulunma Rehberi · Contribution Guidelines

Bu listeye katkıda bulunduğunuz için teşekkürler! Aşağıdaki kurallara uyarsanız PR'ınız hızlıca kabul edilir.

Thanks for contributing! Following these rules will help your PR get merged faster.

## ✅ Kabul Edilenler · What's accepted

- **Teknofest yarışmalarına aktif fayda sağlayan kaynaklar** — açık kaynak projeler, dökümantasyon, eğitim materyalleri, simülatörler, otopilot yazılımları, sensör/donanım rehberleri.
- **Resources directly useful to Teknofest teams** — open source projects, documentation, tutorials, simulators, autopilot software, sensor/hardware guides.
- **Geçmiş takımların paylaştığı açık kaynak depolar** — özellikle teknik rapor ve dökümantasyon içerenler.
- **Open source repositories from past competition teams**, especially those with technical reports or documentation.

## ❌ Kabul Edilmeyenler · What's not accepted

- Kişisel CV / portfolyo siteleri.
- Personal CV / portfolio websites.
- Sadece reklam / pazarlama içerikli linkler.
- Ads or marketing-only content.
- Ölü veya çalışmayan linkler.
- Dead or broken links.
- Bakımsız (2+ yıldır commit almamış) ve açıkça arşivlenmiş projeler — istisna: tarihi değer taşıyan referans projeler.
- Unmaintained projects (no commits in 2+ years) and explicitly archived ones — exception: historical reference value.
- Türkçe veya İngilizce olmayan kaynaklar.
- Resources not in Turkish or English.

## 📝 Format

Her satır şu kuralları izlemeli:

```
- [Kaynak Adı](https://link) — Bir cümle açıklama, nokta ile biter.
```

- **İsim**: Resmi proje/site adı.
- **Link**: HTTPS, doğrudan kaynağa (kısa link / yönlendirme URL'i olmasın).
- **Açıklama**: Tek cümle, Türkçe veya İngilizce. Kaynağın **ne işe yaradığını** açıklamalı, "harika!", "süper!" gibi sıfatlar içermemeli.

İyi örnek · Good example:
```
- [QGroundControl](https://qgroundcontrol.com/) — Cross-platform, PX4 & ArduPilot uyumlu yer istasyonu.
```

Kötü örnek · Bad example:
```
- QGroundControl — Çok iyi bir yer istasyonu! https://qgroundcontrol.com
```

## 🔀 PR Süreci · PR Process

1. Bu repoyu fork edin.
2. Yeni bir branch açın: `git checkout -b add-resource-name`.
3. Eklemenizi uygun kategoriye, alfabetik sırayı koruyarak ekleyin.
4. Commit mesajı: `Add [Kaynak Adı] to [Kategori]`.
5. PR'ınızı açın ve şu bilgileri verin:
   - Neden bu kaynak Teknofest takımlarına faydalı?
   - Kaynağı daha önce kullandınız mı?
6. Maintainer'lar 7 gün içinde yanıt verir.

## 📐 Yeni Kategori Önerme · Proposing a New Category

Mevcut kategorilere uymayan ama Teknofest için anlamlı bir kaynak grubu varsa, önce bir **issue** açın. Tartışıp eklemeye karar verirsek, sonra PR açabilirsiniz.

If a resource doesn't fit existing categories, please open an **issue** first to discuss adding a new category.

## 🙏

Teşekkürler! Bu liste senin gibi katkı verenler sayesinde büyüyor.
Thanks! This list grows because of contributors like you.