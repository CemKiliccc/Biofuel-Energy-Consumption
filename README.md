# Biofuel Consumption Analysis

Bu proje, dünya çapındaki bioenerji tüketiminin yıllık değişimini incelemek ve bu verilerle çeşitli analizler yapmak amacıyla geliştirilmiştir. Proje, **Python** programlama dili ve çeşitli veri bilimi kütüphaneleri kullanılarak yürütülmüştür. Projede kullanılan veri seti, dünya genelindeki bioenerji tüketim oranlarını ve diğer enerji türlerinin kullanımını içermektedir.

## Proje Amacı

Projenin ana amacı, bioenerji tüketimi ile diğer enerji kaynakları arasındaki ilişkiyi anlamak ve farklı ülkelerdeki bioenerji tüketimi oranlarının nasıl değiştiğini görselleştirmektir. Ayrıca, biyoyakıtların dünya enerji üretimindeki yerini anlamak için keşifsel veri analizi (EDA) ve korelasyon analizleri yapılmıştır.

## Veri Seti

### Veri Seti Özellikleri

Veri seti, çeşitli ülkelere ait yıllık enerji tüketimi ve biyoyakıt tüketimi ile ilgili verilerden oluşmaktadır. Anahtar sütunlar şunlardır:

- **Country**: Ülke adı
- **Year**: Yıl
- **Biofuel Consumption (kWh)**: Bioenerji tüketimi (kWh cinsinden)
- **Total Energy Consumption (kWh)**: Toplam enerji tüketimi (kWh cinsinden)
- **Energy Source**: Kullanılan enerji kaynağı türü (bioenerji, fosil yakıt, yenilenebilir enerji, vb.)
- **GDP**: Gayri safi yurtiçi hasıla (sadece bazı ülkeler için)
- **Population**: Ülke nüfusu (sadece bazı ülkeler için)

### Veri Kaynağı

Bu veri seti, [Veri Kaynağının Adı/Linki] tarafından sağlanmıştır. Veri, yıllık bazda toplanan ulusal enerji tüketim verilerinden türetilmiştir.

### Veri Temizliği

- **Eksik Veriler**: Veri setinde eksik veya boş değerler bulunmaktaydı ve bu eksiklikler uygun istatistiksel yöntemlerle tamamlanmıştır.
- **Veri Dönüşümü**: Verilerin doğru analiz edilebilmesi için tür dönüşümleri yapılmış ve tarihsel veriler uygun formatta düzeltilmiştir.
- **Anomaliler**: Veri setinde belirli ülkelerdeki aşırı yüksek veya düşük değerler analiz edilerek dışlanan veriler (outliers) belirlenmiştir.

## Kullanılan Kütüphaneler

Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:

- **Pandas**: Veri manipülasyonu ve işleme için kullanıldı.
- **NumPy**: Matematiksel ve istatistiksel hesaplamalar için kullanıldı.
- **Matplotlib**: Veri görselleştirmeleri için kullanıldı.
- **Seaborn**: Daha karmaşık görselleştirmeler için kullanıldı.
- **Scikit-learn**: Korelasyon analizi ve modelleme için kullanıldı.
- **Jupyter Notebook**: Projenin geliştirilmesi ve analiz edilmesi için kullanıldı.
- **Statsmodels**: İstatistiksel analiz ve regresyon modelleri için kullanıldı.

## Yapılan Analizler

### 1. **Keşifsel Veri Analizi (EDA)**

- Veri setinin temel istatistiksel özetleri çıkarılmıştır.
- Her bir ülkenin bioenerji tüketim oranı yıllık bazda analiz edilmiştir.
- Bioenerji tüketimi ile toplam enerji tüketimi arasındaki ilişki görselleştirilmiştir.
- Ülkeler arasındaki bioenerji tüketimi farkları görselleştirilmiştir.

### 2. **Korelasyon Analizi**

- Farklı enerji türleri (bioenerji, fosil yakıt, yenilenebilir enerji) arasındaki korelasyon hesaplanmıştır.
- Veriler arasında anlamlı ilişkiler olup olmadığını görmek için Pearson korelasyon katsayıları hesaplanmıştır.
  
### 3. **Zaman Serisi Analizi**

- Ülkelerin yıllık bazda bioenerji tüketimindeki değişiklikler zaman serisi analizi kullanılarak incelenmiştir.
- Yıllık tüketim değişim oranları analiz edilmiştir.

### 4. **Veri Görselleştirme**

- **Çubuk Grafikler**: Ülkelerin yıllık bioenerji tüketimi karşılaştırılmıştır.
- **Isı Haritaları**: Enerji kaynakları arasındaki korelasyonları görselleştirilmiştir.
- **Line Chart**: Zaman içindeki bioenerji tüketimindeki değişimler görselleştirilmiştir.

## Proje Adımları

Proje şu temel adımlarla yürütülmüştür:

1. **Veri İndirimi ve Temizliği**: Veri seti indirildi ve eksik veriler kontrol edilip temizlendi.
2. **Keşifsel Veri Analizi (EDA)**: Pandas ve Matplotlib kullanarak verinin genel yapısı incelendi.
3. **Korelasyon Analizi**: Verinin farklı sütunları arasındaki ilişkiler araştırıldı.
4. **Görselleştirme**: Seaborn ve Matplotlib kullanarak verilerin görselleştirilmesi yapıldı.
5. **Sonuçların Raporlanması**: Elde edilen bulgular ve görselleştirmeler yorumlandı.


NOT: Kaggleda yapılan kod ve anlatımları atılan açılan sayfadan  'biofuel-consumption.ipynb' isimli dosyayı açarak içeriğe ulaşabilirsiniz.
Kaggle Profil Linki : https://www.kaggle.com/cemkilic
