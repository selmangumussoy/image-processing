# Quality Control Project (C++)

Bu proje, görüntü işleme teknikleri kullanarak üretim hattındaki ürünlerin **leke**, **yırtık** ve **simetri** bozukluklarını tespit eden bir kalite kontrol sistemidir.

## 🚀 Özellikler

- Görüntü üzerinden:
  - Leke tespiti
  - Yırtık analizi
  - Simetri denetimi
- Görselleri C++ üzerinden işleme
- Geliştirme ortamı: Visual Studio (.sln projesi)

## 📁 Dosya Yapısı

- `FileName.cpp` - Ana kaynak dosyası
- `leketespit.h` - Leke tespiti modülü
- `yırtıktespit.h` - Yırtık analiz algoritması
- `simetritespit.h` - Simetri kontrol fonksiyonları
- `.sln`, `.vcxproj` - Visual Studio proje dosyaları

## 🛠️ Kurulum

1. Visual Studio ile açın:
   - `quality-control-project.sln` dosyasına çift tıklayın
2. Derleme yapmadan önce OpenCV entegrasyonunun yapılmış olduğundan emin olun
3. Gerekirse `x64` / `Debug` klasörlerinde gerekli derleme çıktıları oluşacaktır

## 🧪 Örnek Kullanım

Programı çalıştırdıktan sonra görsel seçip üzerinde hata tespiti yapılabilir. Hatalar console’a veya log dosyasına yazdırılabilir.

## 📷 Örnek Görsel

- `12ad200a-...jpg` test amaçlı örnek görsel içerir

## 🔒 Lisans

MIT Lisansı
