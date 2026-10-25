# AES Group Raptor Ultra CNC İşleme - Analiz Deposu

Bu repository, Türkiye merkezli **AES Group** (AES Elektronik Makina San. ve Tic. A.Ş.) tarafından Bursa Nilüfer NOSAB tesislerinde üretilen **Raptor Ultra (ve Raptor Ultra Line)** model amiral gemisi CNC işleme merkezine ait kapsamlı teknik analizler, tersine mühendislik verileri ve mimari dokümanları içermektedir.

Proje; ağır hizmet tipi endüstriyel ahşap işleme, plastik, alüminyum ve kompozit kesim sistemlerinin mekanik, kinematik, pnömatik ve siber-fiziksel altyapısını incelemektedir.

---

## ⚙️ Makine Teknik Özellikleri ve Donanım Mimarisi

* **Gövde ve Eksen Kinematiği:** Gerilim giderme işlemine tabi tutulmuş ağır hizmet tipi kaynaklı çelik şasi ve hareketli portal (Gantry) konstrüksiyonu. X ve Y eksenlerinde düşük titreşimli helisel kremayer dişli sistemi (**100 m/dk** seri hareket hızı), Z ekseninde ise hassas bilyalı vidalı mil mekanizması (**20 m/dk** hız, **200 mm** net çalışma kursu) yer alır.
* **Boyutsal Varyasyonlar:** Çalışma tablasının Y ve X eksenlerindeki kapasitesine göre **1325, 1336, 1632, 1640, 2128, 2132, 2136, 2142 ve 2157** olmak üzere 9 farklı standart boyutsal varyasyon ve tam otomatik hat tipi **Line-R** konfigürasyonları mevcuttur.
* **İş Mili (Electrospindle):** İtalyan **HSD** üretimi seramik rulman yataklı, **HSK-F63** konik takım tutucu arayüzlü, maksimum **24.000 RPM (400 Hz)** devir hızına sahip; uygulama gereksinimlerine göre **9 kW (12 HP)**, **12 kW (15 HP)** veya **14 kW (19 HP)** güç opsiyonları.
* **Çoklu Delik Üniteleri (Boring Heads):** Standart **9V** versiyonundan yüksek yoğunluklu **DH10, DH17, DH18, DH21, DH22 ve DH34** serilerine kadar değişen dikey/yatay mil ve entegre kanal testeresi (Ø120 mm) dizilimleri.
* **Otomatik Takım Değiştirme (ATC):** X ekseni köprüsüyle hareket eden 12 veya 16 istasyonlu döner karusel ile Z ekseni taşıyıcısına monte edilebilen 10 istasyonlu ikinci karusel sayesinde toplamda **28 takıma kadar** çıkan çift kademeli magazin yapısı.
* **Vakum ve Pnömatik Sistem (Vacuboost):** **30×30 mm** ızgara yapılı Yüksek Akışlı Alüminyum Matris Tabla (8 ila 18 otomatik vakum bölgesi) ve çift **Becker** kuru döner kanatlı vakum pompası (**2 × 250 m³/sa = 500 m³/sa**) kullanan, kesim koordinatına emiş gücünü odaklayan akıllı vakum teknolojisi. Minimum **5 Bar** basınç denetimli pnömatik devreler.
* **Kontrol ve Sürücü Altyapısı:** İtalyan menşeli PC tabanlı **OSAI CNC** (Series 10/510i / OPENcontrol) veya **Syntec 6MA CNC + AES PLC** kontrol mimarisi, **Panasonic** kapalı çevrim AC servo sürücüler, **21 inç** dokunmatik HMI ekran, yan LED durum göstergeleri ve entegre barkod okuyuculu kablosuz **Handterminal Pro+** birimleri.
* **Yazılım Entegrasyonu:** 3D katı model simülasyonu, çarpışma kontrolü ve `.DXF`, `.STL`, `.STEP` dosya formatlarını destekleyen **NC Hops CAD/CAM**, **Alphacam**, **Cabinet Vision** ve **Cadmus** yazılım uyumluluğu.

---

## 📊 Boyutsal Model Matrisi

| Model Kodu | İşleme Alanı (Y × X × Z) | Eksen Hızları (X / Y / Z) | Yaklaşık Ağırlık |
| :--- | :--- | :--- | :--- |
| **Raptor Ultra 1325** | 1300 × 2500 × 200 mm | 100 / 100 / 20 m/dk | 4.100 kg |
| **Raptor Ultra 1336** | 1300 × 3600 × 200 mm | 100 / 100 / 20 m/dk | 4.600 kg |
| **Raptor Ultra 1632** | 1600 × 3200 × 200 mm | 100 / 100 / 20 m/dk | 4.800 kg |
| **Raptor Ultra 1640** | 1600 × 4000 × 200 mm | 100 / 100 / 20 m/dk | 5.400 kg |
| **Raptor Ultra 2128** | 2100 × 2800 × 200 mm | 100 / 100 / 20 m/dk | 5.000 kg |
| **Raptor Ultra 2132** | 2100 × 3200 × 200 mm | 100 / 100 / 20 m/dk | 5.600 kg |
| **Raptor Ultra 2136** | 2100 × 3600 × 200 mm | 100 / 100 / 20 m/dk | 6.000 kg |
| **Raptor Ultra 2142** | 2100 × 4200 × 200 mm | 100 / 100 / 20 m/dk | 6.500 kg |
| **Raptor Ultra 2157** | 2100 × 5700 × 200 mm | 100 / 100 / 20 m/dk | 7.500 kg |
| **Raptor Ultra Line-R** | 2100 × 2800–4200 × 200 mm | 80–100 / 80–100 / 20 m/dk | 11.500 kg |

---

## 📂 Repository İçeriği

Depo içerisinde yer alan dokümanlar ve teknik raporlar şu ana başlıkları kapsamaktadır:
* Raptor Ultra görsel kör analiz bulguları ve ürün segmentasyon matrisi.
* Mekanik, kinematik, pnömatik ve elektromekanik donanım raporları.
* Çevresel emniyet çitleri, dikey/yatay ışık perdeleri, lazer alan tarayıcılar, emniyet paspasları ve basınç tamponlarından oluşan güvenlik mimarisi.
* Avrupa Birliği Yeni Makine Tüzüğü **(AB) 2023/1230**, Siber Dayanıklılık Yasası **(CRA - AB 2024/2847)** ve **EN ISO 19085-3:2021** standart uyum matrisleri.

---

## ⚖️ Yasal Uyarı
*Bu repository ve içerisindeki teknik analizler açık kaynaklı istihbarat ve tersine mühendislik metodolojileri temel alınarak eğitim ve mühendislik araştırması amacıyla hazırlanmıştır.*
