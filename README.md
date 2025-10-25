# Insurance Cost Prediction

Bu proje, Python kullanarak sigorta maliyetlerini makine öğrenmesi yöntemiyle tahmin etmeyi amaçlamaktadır. Çalışmada veri analizi, veri ön işleme, model geliştirme ve performans değerlendirme adımları uygulanmıştır. Proje Linear Regression algoritması kullanılarak gerçekleştirilmiştir.

---

## 🔧 Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|-----------|----------|
| Python | Programlama dili |
| Pandas, NumPy | Veri işleme |
| Matplotlib, Seaborn | Veri görselleştirme |
| Scikit-learn | Makine öğrenmesi |
| Jupyter Notebook | Geliştirme ortamı |

---

## 📊 Veri Seti

Projede **sigorta maliyet tahmini** için yaygın olarak kullanılan bir veri seti kullanılmıştır. Veri seti aşağıdaki sütunlardan oluşur:

| Sütun | Açıklama |
|--------|----------|
| age | Yaş |
| sex | Cinsiyet |
| bmi | Vücut kitle indeksi |
| children | Çocuk sayısı |
| smoker | Sigara kullanımı |
| region | Bölge |
| charges | Sigorta maliyeti (hedef değişken) |

---

## 🚀 Proje Adımları

1. **Veri Keşfi ve Analizi (EDA)**
2. **Eksik ve aykırı değer kontrolü**
3. **Kategorik verilerin dönüştürülmesi (One-Hot Encoding)**
4. **Veri setinin eğitim ve test olarak ayrılması**
5. **Linear Regression modeli ile eğitim**
6. **Model performans değerlendirmesi (MAE, MSE, RMSE)**

---

## 📦 Kurulum

Projeyi çalıştırmak için aşağıdaki adımları izleyin:

### 1. Gerekli kütüphaneleri yükleyin
```bash
pip install -r requirements.txt
