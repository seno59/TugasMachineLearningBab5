# TugasMachineLearningBab5
## 5. Praktikum Bab 5: Pruning (Pemangkasan Decision Tree)

### 1. Pre-Pruning (Praktikum 5.7):
- *Tujuan:* Mencegah overfitting sejak awal sebelum pohon tumbuh sepenuhnya dengan membatasi parameter seperti max_depth (kedalaman maksimum pohon) dan min_samples_leaf (jumlah sampel minimum pada leaf node).
- *Hasil:* Kombinasi parameter yang tepat membantu model menghindari overfitting dan menjaga performa generalisasi pada data uji tetap optimal.

### 2. Cost Complexity Pruning / Post-Pruning (Praktikum 5.8):
- *Tujuan:* Memangkas pohon yang sudah tumbuh terlalu besar dengan menggunakan parameter regularisasi alpha (ccp_alpha).
- *Analisis Kurva:* Berdasarkan grafik kurva akurasi pengujian terhadap nilai ccp_alpha, kita dapat mengidentifikasi nilai alpha optimal yang menghasilkan akurasi tertinggi dengan struktur pohon yang lebih ringkas dan mudah diinterpretasikan.
