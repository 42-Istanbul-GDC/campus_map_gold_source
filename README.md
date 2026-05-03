# 42 Istanbul Campus Map (GoldSource)

Bu proje, **42 Istanbul** kampüsünün GoldSource motoru (Half-Life 1, Counter-Strike 1.6 vb.) kullanan oyunlar için oluşturulmuş birebir ölçekli bir harita replikasıdır.

## 📌 Proje Hakkında
Bu harita, 42 Istanbul kampüsünün mimarisini ve atmosferini dijital dünyaya taşımak amacıyla geliştirilmiştir. GoldSource oyun motoru için optimize edilmiş olan bu proje, hem bir mühendislik çalışması hem de topluluk için bir oyun alanı sunar.

---

## 📂 Dosya Yapısı ve İçerik

*   **`42_istanbul.rmf`**: Haritanın düzenlenebilir ham proje dosyası (Rich Map Format). Valve Hammer Editor ile açılabilir.
*   **`TexturesWadFiles.rar`**: Haritada kullanılan özel dokuların (textures) bulunduğu `.wad` dosyalarını içerir.
*   **`HLTextureTools_V165.zip`**: Doku yönetimi ve düzenlemesi için kullanılan yardımcı araçlar.
*   **`vluzacn_s_zhlt_v34.zip`**: Haritayı `.bsp` formatına derlemek (compile) için kullanılan modern ZHLT (Zoner's Half-Life Tools) derleme araçları.

---

## 🛠️ Nasıl Kullanılır / Geliştirilir?

Eğer haritayı düzenlemek veya kendi bilgisayarınızda derlemek isterseniz şu adımları izleyin:

1.  **Gereksinimler:** [Valve Hammer Editor 3.4](https://developer.valvesoftware.com/wiki/Valve_Hammer_Editor) veya [J.A.C.K.](https://jack.hlfx.ru/en/) editor.
2.  **Doku Kurulumu:** `TexturesWadFiles.rar` içerisindeki dosyaları çıkartın ve Editor ayarlarından doku kütüphanesine ekleyin.
3.  **Proje Açılışı:** `42_istanbul.rmf` dosyasını editor ile açın.
4.  **Derleme (Compile):** `vluzacn_s_zhlt_v34.zip` içerisindeki araçları kullanarak projeyi `.bsp` formatına dönüştürün.

---

## 🎮 Oynanış
Harita derlendikten sonra oluşan `.bsp` dosyasını Half-Life veya Counter-Strike oyununuzun `maps/` klasörüne atarak `map 42_istanbul` komutuyla test edebilirsiniz.

---

## 🛠️ Kullanılan Geliştirme Araçları
*   **Derleme Aracı:** [VHLT-34](https://github.com/twhl-community/VHLT-V34)
*   **Texture Düzenleme Aracı:** [HL_TEXTURE](https://github.com/yuraj11/HL-Texture-Tools)

---
*Bu proje 42 Istanbul GDC (Game Developers Club) tarafından geliştirilmektedir.*
