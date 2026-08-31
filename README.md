# 42 Istanbul Campus Map (GoldSource)

---

## Türkçe

Bu proje, **42 Istanbul** kampüsünün GoldSource motoru (Half-Life 1, Counter-Strike 1.6 vb.) kullanan oyunlar için oluşturulmuş, gerçek ölçülere yakın bir harita replikasıdır. Harita, kampüsün mimarisini ve atmosferini oyun ortamına taşımayı amaçlar.

### 📌 Proje Hakkında
Bu harita, 42 Istanbul kampüsünün detaylı bir dijital modelidir. GoldSource motoru için optimize edilmiştir ve hem düzenleme hem de oynatma amaçlı kullanılabilir.

### 📂 Depo İçeriği (Güncel Dosya İsimleri)

- `istanbul_42.rmf`: Haritanın düzenlenebilir RMF proje dosyası (Rich Map Format). Valve Hammer Editor veya J.A.C.K. ile açılabilir.
- `istanbul_42.bsp`: Derlenmiş (compiled) harita dosyası; Half-Life / Counter-Strike `maps/` klasörüne koyarak oynatabilirsiniz.
- `TexturesWadFiles.rar`: Haritada kullanılan özel dokuların (WAD) arşivi.
- `TexturesWadFiles/` (dizin): Depoda ayrıca dokuların açık halde bulunduğu klasör (eğer varsa).
- `HLTextureTools_V165.zip`: Doku yönetimi ve düzenleme araçları.
- `vluzacn_s_zhlt_v34.zip`: Modern ZHLT/VHLT derleyicileri ve yardımcı araçlar (haritayı .bsp’ye derlemek için).
- `temp/`: Geçici dosyalar veya test amaçlı eklemeler için ayrılmış klasör (içerik depo durumuna göre değişebilir).

> Not: ZIP/RAR gibi arşivlerin içinde üçüncü taraf araçlar bulunabilir; çıkardıktan sonra ilgili araçların README veya kullanım kılavuzunu takip edin.

### 🛠️ Nasıl Kullanılır / Geliştirilir?

1. Gereksinimler
   - Valve Hammer Editor (eski sürümler) veya J.A.C.K. gibi bir RMF editörü.
   - ZHLT/VHLT derleyicileri (pakette `vluzacn_s_zhlt_v34.zip` bulunuyor).

2. Doku Kurulumu
   - `TexturesWadFiles.rar` dosyasını açın ve içindeki `.wad`/dokuları uygun yere yerleştirin.
   - Hammer/J.A.C.K. içinde Textures (doku) kütüphanesine yolları gösterin.

3. Proje Açılışı
   - `istanbul_42.rmf` dosyasını editörde açın ve düzenlemelerinizi yapın.

4. Derleme (Compile)
   - `vluzacn_s_zhlt_v34.zip` içindeki araçlarla (ör. hlcsg, hlbsp, hlvis veya VHLT araçları) RMF → BSP derlemesini yapın.

5. Test
   - Oluşan `istanbul_42.bsp` dosyasını Half-Life veya Counter-Strike `maps/` klasörüne atın.
   - Oyunda konsola `map istanbul_42` yazarak haritayı yükleyin.

### ⚠️ Lisans ve Telif
Haritada kullanılan bazı dokular veya araçlar üçüncü parti kaynaklardan gelmiş olabilir. Herhangi bir içerik kullanmadan önce ilgili lisansları ve izinleri kontrol edin.

---

## English

This project is a near-real-scale replica of the 42 Istanbul campus created for games using the GoldSource engine (Half-Life 1, Counter-Strike 1.6, etc.). The map aims to reproduce the campus architecture and atmosphere within the GoldSource environment.

### About
The map is a detailed digital model of the 42 Istanbul campus, optimized for the GoldSource engine. It can be used both for editing and for playing/testing in compatible games.

### Repository Contents (current filenames)

- `istanbul_42.rmf` — editable RMF project file (Rich Map Format). Open with Valve Hammer Editor or J.A.C.K.
- `istanbul_42.bsp` — compiled BSP map file; place into Half-Life / Counter-Strike `maps/` folder to play.
- `TexturesWadFiles.rar` — archive containing WAD textures used by the map.
- `TexturesWadFiles/` (directory) — directory with texture files (if present in the repo).
- `HLTextureTools_V165.zip` — tools for managing and editing textures.
- `vluzacn_s_zhlt_v34.zip` — modern ZHLT/VHLT compiler tools for compiling RMF → BSP.
- `temp/` — temporary or test files (contents may vary).

Note: Some archives (e.g., zip/rar files) contain external tools; follow the tool-specific README or usage instructions after extraction.

### How to Use / Develop

1. Requirements
   - An RMF editor such as Valve Hammer Editor (older versions) or J.A.C.K.
   - ZHLT/VHLT compilers (a pack is provided as `vluzacn_s_zhlt_v34.zip`).

2. Install Textures
   - Extract `TexturesWadFiles.rar` and install or point your editor to the texture paths.
   - Configure textures in Hammer/J.A.C.K. texture browser.

3. Open Project
   - Open `istanbul_42.rmf` in your editor and make edits as needed.

4. Compile
   - Use the tools inside `vluzacn_s_zhlt_v34.zip` (e.g., hlcsg, hlbsp, hlvis or VHLT equivalents) to compile the RMF into a `.bsp` file.

5. Test
   - Copy the generated `istanbul_42.bsp` to your Half-Life / Counter-Strike `maps/` folder.
   - In game console: `map istanbul_42` to load the map.

### License & Third-party Assets
Some textures or tools included may come from third-party sources. Check licenses and permissions before reusing or redistributing any third-party content.

---

This project is developed by the 42 Istanbul Game Design and Development Club.
