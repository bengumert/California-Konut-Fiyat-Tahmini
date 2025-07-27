# Kaliforniya Konut Fiyat Tahmini

Bu proje, Kaliforniya eyaletindeki konut fiyatlarını tahmin etmek için kapsamlı bir veri analizi ve makine öğrenimi yaklaşımı sunmaktadır. Proje, farklı regresyon modellerinin (örneğin, Lineer Regresyon, Gradient Boosting) performansını karşılaştırarak en iyi tahmin modelini belirlemeyi amaçlar.

## İçerik

Bu depo aşağıdaki Jupyter Notebook dosyasını içermektedir:

* **`california-housing-prices.ipynb`**: Bu not defteri, Kaliforniya konut veri setinin yüklenmesi, keşfedilmesi (EDA - Exploratory Data Analysis), ön işlenmesi (eksik değerlerin yönetimi, özellik mühendisliği), farklı regresyon modellerinin eğitilmesi ve performanslarının değerlendirilmesi adımlarını detaylı olarak göstermektedir. Model performansları, Ortalama Mutlak Hata (MAE), Ortalama Kare Hata (MSE) ve Kök Ortalama Kare Hata (RMSE) gibi metriklerle ölçülmüştür.

## Özellikler

* Kapsamlı veri keşfi ve görselleştirme.
* Veri ön işleme teknikleri (özellik ölçeklendirme, kategorik değişkenlerin dönüştürülmesi).
* Çeşitli makine öğrenimi regresyon modellerinin uygulanması.
* Model performanslarının karşılaştırılması ve en iyi modelin seçimi.
* Tahmin sonuçlarının değerlendirilmesi için standart regresyon metriklerinin kullanılması.


## Kullanılan Teknolojiler

* **Python**
* **Pandas**: Veri yükleme, manipülasyonu ve analizi için.
* **NumPy**: Sayısal işlemler için.
* **Scikit-learn**: Makine öğrenimi modelleri (Lineer Regresyon, Gradient Boosting, vb.) ve veri ön işleme (veri bölme, ölçeklendirme) için.
* **Matplotlib / Seaborn**: Veri görselleştirmeleri için.
