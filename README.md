# 42 Istanbul Campus Map (GoldSource)

Bu proje, **42 Istanbul** kampüsünün GoldSource motoru (Half-Life 1, Counter-Strike 1.6 vb.) kullanan oyunlar için oluşturulmuş birebir ölçekli bir harita replikasıdır.

## 📌 Proje Hakkında
Bu harita, 42 Istanbul kampüsünün mimarisini ve atmosferini dijital dünyaya taşımak amacıyla geliştirilmiştir. GoldSource oyun motoru için optimize edilmiş olan bu proje, hem bir mühendislik çalışması hem de topluluk için eğlenceli bir oyun alanı sunmayı hedefler.

## 📂 Dosya Yapısı ve İçerik

- **`half.rmf`**: Haritanın düzenlenebilir ham proje dosyası (Rich Map Format). Valve Hammer Editor ile açılabilir.
- **`TexturesWadFiles.rar`**: Haritada kullanılan özel dokuların (textures) bulunduğu `.wad` dosyalarını içerir.
- **`HLTextureTools_V165.zip`**: Doku yönetimi ve düzenlemesi için kullanılan yardımcı araçlar.
- **`vluzacn_s_zhlt_v34.zip`**: Haritayı `.bsp` formatına derlemek (compile) için kullanılan modern ZHLT (Zoner's Half-Life Tools) derleme araçları.

## 🛠️ Nasıl Kullanılır / Geliştirilir?

Eğer haritayı düzenlemek veya kendi bilgisayarınızda derlemek isterseniz şu adımları izleyin:

1. **Gereksinimler:** [Valve Hammer Editor 3.4](https://www.moddb.com/downloads/valve-hammer-editor-34) veya [J.A.C.K.](https://jack.hlfx.ru/en/) editor.
2. **Doku Kurulumu:** `TexturesWadFiles.rar` içerisindeki dosyaları çıkartın ve Editor ayarlarından doku kütüphanesine ekleyin.
3. **Proje Açılışı:** `half.rmf` dosyasını editor ile açın.
4. **Derleme (Compile):** `vluzacn_s_zhlt_v34.zip` içerisindeki araçları kullanarak projeyi `.bsp` formatına dönüştürün.

## 🎮 Oynanış
Harita derlendikten sonra oluşan `.bsp` dosyasını Half-Life veya Counter-Strike oyununuzun `maps/` klasörüne atarak `map 42_istanbul` komutuyla test edebilirsiniz.

---
*Bu proje 42 Istanbul GDC (Game Developers Club) tarafından geliştirilmektedir.*
