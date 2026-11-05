<p align="center"><img src="assets/app-icon/lightcraft-small.svg" width="128" alt="NOVA Işık"></p>
<h1 align="center">NOVA Işık</h1>
<p align="center"><strong>Fotoğraf arşivi ve RAW geliştirme (Lightroom benzeri)</strong></p>

<p align="center">
  <a href="../../releases/latest">⬇️ İndir (Windows)</a> ·
  <a href="https://www.instagram.com/xsametsahinx">Instagram</a> ·
  <a href="https://www.youtube.com/@xsametsahinx">YouTube</a> ·
  <a href="mailto:samet.sahin.iletisim@gmail.com">Öneri &amp; Şikayet</a>
</p>

NOVA Işık, NOVA uygulama ailesinin bir parçasıdır: hızlı, yerel çalışan, Rust ile yazılmış
açık kaynak bir masaüstü programı.

## NOVA'da neler farklı?

- **NOVA kimliği:** Yeni ad, NOVA yıldız logosu ve uygulama simgeleri.
- **Ayrı kurulum:** Kendi Windows kurulum kimliği ve `NOVA` program klasörü; bilgisayarda
  kurulu başka uygulamalarla karışmaz.
- **Güncellemeler bu depodan:** Uygulama içi güncelleme denetimi yalnızca bu deponun
  Releases sayfasına bakar.
- **NOVA ailesi:** Menülerdeki kardeş uygulamalar NOVA adlarıyla görünür
  (NOVA Foto, NOVA Işık, NOVA Vektör, NOVA Tasarım, NOVA Film, NOVA Efekt, NOVA PDF, NOVA Yazı).
- **Otomatik Windows kurulumu:** Her sürüm etiketinde GitHub `.msi` ve taşınabilir `.zip`
  dosyalarını kendisi üretir.

## İndirme ve kurulum

[Releases](../../releases/latest) sayfasından `lightcraft-<sürüm>-windows-x64.msi` dosyasını indirip
çalıştır. Kurulum istemiyorsan `-portable.zip` dosyasını bir klasöre açman yeterli.

> Kurulum dosyası dijital olarak imzalı olmadığı için Windows SmartScreen uyarı verebilir:
> **Ek bilgi › Yine de çalıştır**.

## Yeni sürüm yayınlama

1. `Cargo.toml` içinde `[workspace.package]` altındaki `version` değerini artır.
2. `git tag v<sürüm>` ve `git push origin v<sürüm>`
3. GitHub › **Actions** bitince dosyalar **Releases** sayfasında olur.

## Lisans ve teşekkür

NOVA Işık, [LightCraft](https://github.com/storytold/lightcraft) açık kaynak projesi temel alınarak
geliştirilmiştir ve aynı lisanslarla (MIT veya Apache-2.0) dağıtılır — bkz.
[LICENSE-MIT](LICENSE-MIT), [LICENSE-APACHE](LICENSE-APACHE), [NOTICE](NOTICE).
NOVA Işık, ArtCraft Team ile bağlantılı değildir ve onlar tarafından onaylanmamıştır.
Orijinal proje açıklaması: [README.lightcraft.md](README.lightcraft.md).

Geliştirici: **Samet Şahin** (@xsametsahinx)
