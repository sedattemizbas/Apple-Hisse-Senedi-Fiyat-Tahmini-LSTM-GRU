# Apple-Hisse-Senedi-Fiyat-Tahmini-LSTM-GRU
PyTorch kullanılarak Apple (AAPL) hisse senedi fiyatlarının LSTM ve GRU modelleri ile tahmin edilmesi.
# Apple Hisse Senedi Fiyat Tahmini (LSTM ve GRU)

## Proje Hakkında

Bu projede PyTorch kullanılarak Apple (AAPL) hisse senedi kapanış fiyatları tahmin edilmiştir.

Projede iki farklı derin öğrenme modeli kullanılmıştır:

- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)

Daha sonra iki model RMSE değeri kullanılarak karşılaştırılmıştır.

---

## Kullanılan Teknolojiler

- Python
- PyTorch
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

---

## Veri Seti

Veriler Yahoo Finance üzerinden `yfinance` kütüphanesi kullanılarak alınmıştır.

Kullanılan hisse:

Apple (AAPL)

---

## Proje Aşamaları

- Verinin alınması
- Veri ön işleme
- Normalizasyon
- Sliding Window oluşturulması
- Eğitim/Test ayrımı
- LSTM modelinin eğitilmesi
- GRU modelinin eğitilmesi
- Tahmin yapılması
- RMSE hesaplanması
- Modellerin karşılaştırılması

---

## Model Sonuçları

| Model | RMSE |
|-------|------:|
| LSTM | 9.8627 |
| GRU | 7.3922 |

Bu çalışmada GRU modeli daha düşük RMSE değeri elde ederek LSTM modeline göre daha başarılı sonuç vermiştir.

---
## Yapılabilecek Geliştirmeler:

- Farklı şirketlerin hisse senetleri üzerinde testler yapılabilir.
- Açılış (Open), En Yüksek (High), En Düşük (Low) ve İşlem Hacmi (Volume) gibi ek özellikler modele dahil edilebilir.
- Transformer tabanlı zaman serisi tahmin modelleri ile performans karşılaştırması yapılabilir.

## Geliştirici

Sedat Temizbaş
