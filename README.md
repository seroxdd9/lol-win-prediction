# LoL Maç Kazanma Tahmini

League of Legends'da ilk 10 dakika istatistiklerine bakarak hangi takımın kazanacağını tahmin eden makine öğrenmesi projesi.

## Proje Hakkında
- 9,879 Diamond rankedi maç kullanıldı
- 3 farklı algoritma karşılaştırıldı (Decision Tree, Random Forest, XGBoost)
- XGBoost hiperparametre optimizasyonu ile %72 doğruluk elde edildi
- AUC skoru: 0.81

## Bulgular
- Altın farkı kazanmayı en çok etkileyen faktör (%31 önem skoru)
- 3000 altın önde olmak kazanma şansını %9.7 artırıyor
- Kill atmak neredeyse hiç etkili değil (+%0.2)
- Ejderha almak altın kadar önemli değil

## Kullanılan Teknolojiler
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost
- Kaggle (veri seti: bobbyscience/league-of-legends-diamond-ranked-games-10-min)
