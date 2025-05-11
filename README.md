📊 Makine Öğrenmesi ile Regresyon Tahmini
Bu proje, çeşitli veri ön işleme teknikleri ve güçlü regresyon modelleri (CatBoost, LightGBM) kullanarak regresyon problemi çözümüne odaklanmaktadır. Projede StratifiedKFold ile modelin istikrarlı bir şekilde değerlendirilmesi sağlanmaktadır.

🔧 Kullanılan Teknolojiler
Python

Pandas, NumPy

Scikit-learn

CatBoost

LightGBM

TQDM

KNNImputer, LabelEncoder, OrdinalEncoder

StratifiedKFold (sınıflandırma bazlı regresyon bölmesi)

📁 Veri Setleri

train.csv – Eğitim verisi

test_x.csv – Test verisi

il_ilce.csv – Şehir ve ilçe bilgileri

🚀 Proje Adımları
Veri Yükleme ve Temizlik:

Kategorik değişkenler küçük harfe çevrildi ve unidecode ile normalize edildi.

Eksik veriler KNNImputer ile dolduruldu.

Özellik Mühendisliği:

Label Encoding ve Ordinal Encoding uygulandı.

Gerekli sütunlar düzenlendi.

Modelleme:

CatBoostRegressor ve LightGBM modelleri kullanıldı.

StratifiedKFold ile 7 katlı çapraz doğrulama uygulandı.

RMSE (Root Mean Squared Error) ile performans ölçümü yapıldı.

📈 Model Başarımı
RMSE değerleri katmanlı olarak kaydedildi.

Çok çekirdekli işlemci desteğiyle paralel işlemler kullanıldı.
