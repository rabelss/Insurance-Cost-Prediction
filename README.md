# Insurance Cost Prediction

Bu proje, sigorta verileri üzerinde **masraf (cost) tahmini** yapmak için Python ve makine öğrenmesi (Linear Regression) kullanır. Çalışma; veri hazırlama, görselleştirme, model eğitimi ve metriklerle değerlendirme adımlarını içerir.

## İçerik
- **Jupyter Notebook**: `Insurance-Cost-Prediction.ipynb`
- (Varsa) **Veri**: `insurance.csv`
- **Gereksinimler**: `requirements.txt`

## Kullanılan Teknolojiler
- Python (Pandas, NumPy)
- Görselleştirme (Matplotlib, Seaborn)
- Makine Öğrenmesi (scikit-learn)
- Jupyter Notebook

## Adımlar (Notebook İçeriği)
1. **Veri Yükleme & İnceleme**: Eksik değer, tip, özet istatistikler
2. **Veri Hazırlama**: Kategorik değişkenlerin dönüştürülmesi, gerekirse ölçekleme
3. **Görselleştirme**: Dağılımlar, korelasyon ısı haritası
4. **Modelleme**: `train_test_split` + `LinearRegression`
5. **Değerlendirme**: MAE, MSE, RMSE

## Çalıştırma
```bash
pip install -r requirements.txt
jupyter notebook
# Notebook içinde sırasıyla hücreleri çalıştırın


## requirements.txt
```bash
cat > requirements.txt << 'EOF'
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
