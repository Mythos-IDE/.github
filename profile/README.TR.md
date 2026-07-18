<div align="center">
  <img src="assets/readme/hero.svg" alt="Mythos — roman yazarları için bir dünya geliştirme ortamı; süreklilik hatalarını bir derleyicinin bug yakaladığı gibi yakalar" width="100%">
</div>

<p align="center"><a href="./README.md">English</a> · Türkçe</p>

**Karmaşık dünyalar inşa eden romancılar için bir yazar IDE'si.**

Genel not alma araçlarının sınırlarını aşan ve geleneksel kelime işlemcileri seri uzunluğundaki dünya kurgusu için fazla düzensiz bulan fantastik, bilimkurgu ve epik kurgu yazarları için bir masaüstü uygulaması geliştiriyoruz. Şöyle düşünün: Scrivener'ın yapısal disiplini ile bir yazılım IDE'sinin bağlamsal zekâsının birleşimi.

Mythos, tüm serinizi bir derleyicinin kod tabanını okuduğu gibi okur — böylece Birinci Kitap'ta ölen bir karakter, İkinci Kitap'ta ortam onu işaretlemeden usulca yeniden konuşamaz.

## Ekosistem

Mythos; motoru, arayüzü ve siteyi birbirinden ayıran çoklu depo (multi-repo) ekosistemi olarak inşa edilmiştir.

| Depo | Nedir | Teknoloji |
| --- | --- | --- |
| [`mythoside-core`](https://github.com/Mythos-IDE/mythoside-core) | Motor — elyazması veri modeli, Markdown + YAML dosya formatı, dosya izleme ve stdio üzerinden bir JSON-RPC sunucusu (ağ portu yok). | Rust |
| [`mythoside-ts`](https://github.com/Mythos-IDE/mythoside-ts) | Masaüstü istemcisi — motoru sidecar olarak barındıran editör yüzeyi. | Tauri · React · TypeScript |
| [`mythoside-website`](https://github.com/Mythos-IDE/mythoside-website) | Tanıtım sayfası ve ürün hikâyesi. | Vite · React |

## Temel Felsefe

- **Notlar için değil, kurgu için** — kendiniz yapılandırmak zorunda kaldığınız bir sistem değil, yerleşik bir Seri → Kitap → Bölüm hiyerarşisi.
- **Bağlamsal dünya inşası** — taslağınızdan ayrılmadan `@KarakterAdi` yazın ve anında bir profil kartı alın.
- **Her zaman yerel öncelikli** — gerçek doğruluk kaynağı diskinizdeki düz Markdown + YAML üst verisidir. Romanınız bir sunucuya rehin değildir; anında çapraz referans için yerel bir SQLite (FTS5) indeksi, doğruluk kaynağı değil yeniden kurulabilir bir önbellek olarak planlanmaktadır.
- **Tanılama olarak süreklilik** — ortam, dünya kurgusuna bir IDE'nin titizliğiyle yaklaşır: bir karaktere ölümünden sonra referans verin ya da onu aynı anda iki yere koyun, size söyler.

## Katkıda Bulunun

Erken geliştirme aşaması. Gelişmeleri takip edin, depolara yıldız verin veya epik uzunlukta kurgu yazıyor ve bunun nasıl şekilleneceğinde söz sahibi olmak istiyorsanız [Discussions](https://github.com/Mythos-IDE/mythoside-core/discussions) bölümüne katılın.

- **Sorunlar ve özellik fikirleri** → [Core](https://github.com/Mythos-IDE/mythoside-core/issues) · [Desktop](https://github.com/Mythos-IDE/mythoside-ts/issues)
- **Genel sorular** → [Discussions](https://github.com/Mythos-IDE/mythoside-core/discussions)

## İletişim

| Konu | E-posta |
| --- | --- |
| Genel sorular | hello@mythoside.com |
| Destek ve yardım | support@mythoside.com |
| Güvenlik raporları | security@mythoside.com |
| Basın ve medya | press@mythoside.com |
| Kariyer | jobs@mythoside.com |
| Hukuk | legal@mythoside.com |
| Sosyal ve topluluk | social@mythoside.com |

Güvenlik açıklarını lütfen özel olarak **security@mythoside.com** adresine bildirin — herkese açık bir issue açmayın.

---
<div align="center">
  <sub>Mythos Ekibi tarafından geliştirilen açık kaynaklı yazılım.</sub>
</div>
