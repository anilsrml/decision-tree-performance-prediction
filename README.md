# 🎓 Öğrenci Performans Sınıflandırma Projesi

Bu proje, öğrencilerin sosyo-ekonomik, akademik ve demografik özelliklerine göre **akademik başarı seviyelerinin** makine öğrenmesi kullanılarak sınıflandırılmasını amaçlamaktadır.

---

## 📌 Proje Özeti

- 🎯 **Amaç**: Öğrenci başarı düzeylerini doğru bir şekilde tahmin etmek
- 🧠 **Yöntemler**:
  - Veri temizleme ve ön işleme
  - Özellik seçimi ve etiketleme
  - Model eğitimi ve değerlendirme
  - Görselleştirme ve yorumlama
- ✅ **En Başarılı Model**: Decision Tree (Karar Ağacı) sınıflandırıcısı

---

## 🧩 Kullanılan Özellikler (Feature'lar)

Veri kümesi şu gibi özellikleri içermektedir:

- Cinsiyet, Yaş, Aile Geliri, Kast, Ebeveyn Eğitimi
- Çalışma Süresi, Ders Tekrarı, Devamsızlık
- Önceki notlar ve başarı göstergeleri

---

## 🛠️ Kullanılan Teknolojiler

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🚀 Proje Aşamaları

1. **Veri Ön İşleme**
   - Eksik değerlerin doldurulması
   - Kategorik verilerin sayısal verilere dönüştürülmesi
   - Eğitim ve test verilerine ayrılması

2. **Model Eğitimi**
   - `Random Forest` kullanılarak model eğitimi
   - Doğruluk (accuracy), F1 skoru, duyarlılık ve özgüllük ile değerlendirme

3. **Görselleştirme**
   - Karmaşıklık Matrisi (Confusion Matrix)
   - Özellik Önem Dereceleri
   - Kast Grubuna Göre Performans Dağılımı

---

## 📈 Değerlendirme Ölçütleri

| Ölçüt          | Açıklama                                |
|----------------|------------------------------------------|
| Doğruluk       | Genel olarak modelin tahmin doğruluğu    |
| Duyarlılık     | Pozitif sınıfların ne kadar doğru bulunduğu |
| Özgüllük       | Yapılan doğru tahminlerin güvenilirliği  |
| F1 Skoru       | Duyarlılık ve özgüllüğün dengesi         |

---

## 📊 Görseller

### 🔥 Karmaşıklık Matrisi

Modelin tahmin ettiği sınıflar ile gerçek sınıfların karşılaştırması.

### 🌟 Özellik Önem Dereceleri

Modelin karar verirken hangi özellikleri ne kadar kullandığını gösterir.

### 🧬 Kast Performans Dağılımı

Kast gruplarına göre öğrencilerin performans düzeyleri analizi.
