<div align="center">
  <picture>
    <img src="assets/readme/hero.svg" alt="Mythos - Roman Yazarları İçin Dünya Geliştirme Ortamı" width="100%">
  </picture>
</div>

<p align="center"><a href="./README.md">English</a> · Türkçe</p>

**Karmaşık dünyalar inşa eden romancılar için geliştirilmiş bir yazar IDE'si.**

Kişisel not alma araçlarının sınırlarını aşan ve geleneksel kelime işlemcileri epik kurgular için fazla düzensiz bulan fantastik, bilimkurgu ve epik roman yazarları için bir masaüstü uygulaması geliştiriyoruz. Şöyle düşünün: Scrivener'ın yapısal disiplini ile bir yazılım IDE'sinin bağlamsal zekasının birleşimi.

## 📦 Ekosistem

Mythos, çekirdek motor, kullanıcı arayüzü ve dokümantasyon arasındaki görevleri ayırmak için çoklu depo (multi-repo) ekosistemi olarak inşa edilmiştir.

- [`mythoside-core`](https://github.com/Mythos-IDE/mythoside-core)  
  Çekirdek motor, bilgi grafiği yöneticisi ve yerel SQLite sunucusu. **Rust** ile geliştirildi.
- [`mythoside-ts`](https://github.com/Mythos-IDE/mythoside-ts)  
  Masaüstü uygulaması ve kullanıcı arayüzü. **Tauri**, **React** ve **TypeScript** ile geliştirildi.
- [`mythoside-website`](https://github.com/Mythos-IDE/mythoside-website)  
  Resmi tanıtım sayfası ve dokümantasyon. **Vite** ve **React** ile geliştirildi.

## 🧠 Temel Felsefe

- 📚 **Notlar için değil, kurgu için tasarlandı** — Kendi kendinize yapılandırmak zorunda kaldığınız bir sistem yerine, yerleşik Seri → Kitap → Bölüm → Sahne hiyerarşisi.
- 🔗 **Bağlamsal dünya inşası** — Taslağınızdan ayrılmadan `@KarakterAdi` yazarak anında bağlamsal bir profil kartı alın.
- 💾 **Her zaman yerel öncelikli (Local-first)** — Gerçek bilgi kaynağı, diskinizdeki düz Markdown + YAML üst verileridir. Romanınız hiçbir zaman bir sunucuya bağımlı kalmaz.
- ⚡ **Hızlı** — Yerel bir SQLite (FTS5) indeksi, çapraz referans sorgularını hiçbir zaman bir önbellekten fazlası olmadan anında gerçekleştirir.

## 🤝 Katkıda Bulunun

Erken geliştirme aşaması. Gelişmeleri takip etmek, projelere yıldız vermek veya kurgu süreçlerinize uygun şekilde şekillenmesinde söz sahibi olmak için [Discussions](https://github.com/Mythos-IDE/mythoside-core/discussions) bölümüne katılabilirsiniz.

- **Sorunlar ve özellik fikirleri** → [Core Issues](https://github.com/Mythos-IDE/mythoside-core/issues) | [TS Issues](https://github.com/Mythos-IDE/mythoside-ts/issues)
- **Genel sorular** → [Discussions](https://github.com/Mythos-IDE/mythoside-core/discussions)
- **Güvenlik raporları** → security@mythoside.com
- **Diğer her şey** → hello@mythoside.com

---
<div align="center">
  <sub>Mythos Ekibi tarafından geliştirilen Açık Kaynaklı yazılım.</sub>
</div>
