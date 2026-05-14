# QGIS Tile Servers

QGIS için hazır harita servisi bağlantı dosyaları koleksiyonu.

## Dosyalar

### Maps Services.xml ve Tile Servers.xml

QGIS XYZ Tile bağlantı listesi dosyaları. Aşağıdaki servisler tanımlıdır:

| Servis | Açıklama |
|---|---|
| OpenStreetMap | Açık kaynak sokak haritası |
| Google Maps / Satellite / Terrain | Google harita servisleri |
| Bing Virtual Earth | Microsoft uydu görüntüsü |
| Esri Light Gray / National Geographic / Terrain | Esri harita servisleri |
| Carto Light | Açık renk vektör taban haritası |
| HGM | Harita Genel Müdürlüğü ortofoto |
| HGM Yükseklik | HGM yükseklik haritası |
| HGM with Label | HGM ortofoto + etiket |
| OpenTopoMap / Mapzen Terrain | Topografik ve yükseklik haritaları |

**Kullanım:**
1. QGIS'te **Browser** panelinde `XYZ Tiles` üzerine sağ tıklayın
2. **Load connections** seçin
3. İlgili XML dosyasını seçin
4. İstediğiniz servisleri seçip **Import** edin

---

### hgm_topografik.xml

HGM (Harita Genel Müdürlüğü) topografik harita servisi — `atlas.harita.gov.tr` üzerinden GDAL_WMS formatında tanımlanmış raster katman.

- **Projeksiyon:** EPSG:3857
- **Maks. Zoom:** 13
- **Format:** PNG

**Kullanım — Drag & Drop:**

`hgm_topografik.xml` dosyasını doğrudan QGIS harita alanına veya **Layers** paneline sürükleyip bırakın. QGIS dosyayı otomatik olarak tanır ve katmanı ekler.

---

## Gereksinimler

- QGIS 3.x
- İnternet bağlantısı
- HGM servisleri için geçerli API anahtarı (dosyalara gömülü)
