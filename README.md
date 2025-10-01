# Autoencoder untuk Dataset Custom (Facades Dataset)

## 📌 Deskripsi
Proyek ini merupakan implementasi **autoencoder** menggunakan dataset custom berupa **CMP Facade Database**.  
Autoencoder dilatih dengan **input berupa foto bangunan** dan **output berupa citra segmen fasad bangunan**.

Repo ini berisi:
- Notebook Colab untuk melatih autoencoder
- Dataset (link & cara download)
- Hasil pelatihan (loss)
- Contoh input dan output gambar hasil rekonstruksi

---

## 📂 Dataset
Dataset yang digunakan: [CMP Facade Database](https://cmp.felk.cvut.cz/~tylecr1/facade/)

Cara download dataset di Colab:
```python
!wget https://cmp.felk.cvut.cz/~tylecr1/facade/CMP_facade_DB_base.zip
!unzip CMP_facade_DB_base.zip -d data/facades

[Uploading untitled19 (1).py…]()
https://colab.research.google.com/drive/1-ebCZMO0Oqq6Qiqvyd4TYBlPgUi_rUMu?usp=sharing
