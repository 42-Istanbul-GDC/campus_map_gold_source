# 42 Istanbul Campus Map (GoldSource)

Bu proje, **42 Istanbul** kampüsünün GoldSource motoru (Half-Life 1, Counter-Strike 1.6 vb.) kullanan oyunlar için oluşturulmuş, gerçek ölçülere yakın bir harita replikasıdır. Harita, kampüsün mimarisini ve atmosferini oyun ortamına taşımayı amaçlar.

## 📌 Proje Hakkında
Bu harita, 42 Istanbul kampüsünün detaylı bir dijital modelidir. GoldSource motoru için optimize edilmiştir ve hem düzenleme hem de oynatma amaçlı kullanılabilir.

---

## 📂 Depo İçeriği (Güncel Dosya İsimleri)

- `istanbul_42.rmf`: Haritanın düzenlenebilir RMF proje dosyası (Rich Map Format). Valve Hammer Editor veya J.A.C.K. ile açılabilir.
- `istanbul_42.bsp`: Derlenmiş (compiled) harita dosyası; Half-Life / Counter-Strike `maps/` klasörüne koyarak oynatabilirsiniz.
- `TexturesWadFiles.rar`: Haritada kullanılan özel dokuların (WAD) arşivi.
- `TexturesWadFiles/` (dizin): Depoda ayrıca dokuların açık halde bulunduğu klasör (eğer varsa).
- `HLTextureTools_V165.zip`: Doku yönetimi ve düzenleme araçları.
- `vluzacn_s_zhlt_v34.zip`: Modern ZHLT/VHLT derleyicileri ve yardımcı araçlar (haritayı .bsp’ye derlemek için).
- `HLTextureTools_V165.zip`, `vluzacn_s_zhlt_v34.zip` gibi sıkıştırılmış araçların içeriğini çıkardıktan sonra, ilgili araçların README veya kullanım kılavuzlarını takip edin.
- `temp/`: Geçici dosyalar veya test amaçlı eklemeler için ayrılmış klasör (içerik depo durumuna göre değişebilir).

---

## 🛠️ Nasıl Kullanılır / Geliştirilir?

1. Gereksinimler:
   - Valve Hammer Editor (eski sürümler) veya J.A.C.K. gibi bir RMF editörü.
   - ZHLT/VHLT derleyicileri (pakette `vluzacn_s_zhlt_v34.zip` bulunuyor).

2. Doku Kurulumu:
   - `TexturesWadFiles.rar` dosyasını açın ve içindeki `.wad`/dokuları uygun yere yerleştirin.
   - Hammer/J.A.C.K. içinde Textures (doku) kütüphanesine yolları gösterin.

3. Proje Açılışı:
   - `istanbul_42.rmf` dosyasını editörde açın ve düzenlemelerinizi yapın.

4. Derleme (Compile):
   - `vluzacn_s_zhlt_v34.zip` içindeki araçlarla (ör. zhlt/hlcsg/hlbsp/vbsp vb.) RMF → BSP derlemesini yapın.

5. Test:
   - Oluşan `istanbul_42.bsp` dosyasını Half-Life veya Counter-Strike `maps/` klasörüne atın.
   - Oyunda `map istanbul_42` komutuyla haritayı yükleyin.

---

## ⚠️ Lisans ve Telif
Haritada kullanılan bazı dokular veya araçlar üçüncü parti kaynaklardan gelmiş olabilir. Herhangi bir içerik kullanmadan önce ilgili lisansları ve izinleri kontrol edin.

---

## Kaynaklar ve Araçlar
- VHLT / ZHLT derleyicileri: vluzacn paketleri ve topluluk araçları.
- HL Texture Tools: Doku yönetimi için yardımcı araçlar.

---

Bu proje 42 Istanbul Game Design and Development Club tarafından geliştirilmektedir.
