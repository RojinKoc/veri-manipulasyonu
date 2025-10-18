# Veri Manipülasyonu – NumPy & Pandas Uygulama Defteri

Bu repo, **NumPy** ve **Pandas** ile temel–orta seviye veri manipülasyonu örneklerini adım adım gösteren bir Jupyter Notebook içerir.  
Amaç; dizi (array) işlemleri, yeniden şekillendirme, birleştirme/ayırma, indeksleme/dilimleme, özet istatistikler, **Pandas Series/DataFrame** operasyonları, **groupby/aggregate/transform/apply**, **merge/concat** ve **pivot table** gibi **pratikte en çok kullanılan** teknikleri kısa, çalışır örneklerle pekiştirmektir.

## 📁 İçerik

- `veri_manipulasyonu.ipynb` – Tüm kod ve örnekler bu notebook’ta.
- (Opsiyonel) `requirements.txt` – Gerekli paket listesi.
- (Bu dosya) `README.md`

## 🧰 Kullanılan Kütüphaneler

- `numpy` – vektörize hesaplama, dizi oluşturma/şekillendirme, rastgele sayı üretimi, temel istatistikler
- `pandas` – Series/DataFrame oluşturma, indeksleme, seçim, birleşim, toplulaştırma, pivot tablolar
- `seaborn` – örnek veri setleri (örn. `planets`, `titanic`)
- (İsteğe bağlı) `matplotlib` – görselleştirmeler için
- `jupyter` / `jupyterlab` – notebook çalıştırma

## 🚀 Hızlı Başlangıç

```bash
# Depoyu klonla
git clone https://github.com/RojinKoc/veri-manipulasyonu.git
cd veri-manipulasyonu

# (Opsiyonel) Sanal ortam
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# Gerekli paketler
pip install -r requirements.txt  # varsa
# ya da minimum kurulum:
pip install numpy pandas seaborn jupyter

# Notebook'u çalıştır
jupyter notebook veri_manipulasyonu.ipynb
