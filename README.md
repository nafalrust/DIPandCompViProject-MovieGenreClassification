# DIPandCompViProject-MovieGenreClassification

Repositori ini berisi kode dari project mata kuliah **Pengolahan Citra dan Visi Komputer** tentang klasifikasi genre film dari poster.

## Judul

**Beyond the Image: Enhancing Movie Genre Classification with Title-Aware Cross-Attention on Poster Features**

## Abstract

Accurate movie genre classification underpins key functionalities in modern streaming platforms, including recommendation systems, content filtering, and metadata management. Movie posters offer a lightweight, universally available visual signal for prerelease genre prediction; however, visual features alone often fail to disambiguate genres that share similar aesthetic conventions. This paper investigates whether incorporating the movie title as a complementary textual signal can improve multilabel genre classification from poster images. We propose a multimodal architecture that fuses EfficientNet-B3 visual features with BERT-encoded title embeddings via an 8-head cross-attention mechanism, and compare it against an image-only EfficientNet-B3 baseline under identical training conditions. Both models are evaluated on a dataset of 300 IMDb poster images covering 14 genre categories. The multimodal model achieves a Macro F1 of 0.7293 after per-genre threshold optimization, outperforming the image-only baseline by +0.2024 in Macro F1. The performance gain is most pronounced on lexically distinctive genres such as sci-fi, horror, and adventure, where title semantics guide the cross-attention mechanism to attend to genre-discriminative visual regions, as confirmed by GradCAM visualizations. These results demonstrate that movie titles, despite their brevity, encode genre-discriminative information that meaningfully complements visual poster features for multilabel genre classification.

**Index Terms**—movie genre classification, EfficientNet, BERT, cross-attention, multilabel classification, movie poster

## Tim

### Muhammad Nafal Zakin Rustanto
Dept. of Electrical and Information Engineering  
Universitas Gadjah Mada  
Yogyakarta, Indonesia  
muhammadnafalzakinrustanto@mail.ugm.ac.id

### Nathanael Satya Saputra
Dept. of Electrical and Information Engineering  
Universitas Gadjah Mada  
Yogyakarta, Indonesia  
nathanaelsatyasaputra@mail.ugm.ac.id

### Johannes De Deo Dimas Aryobimo
Dept. of Electrical and Information Engineering  
Universitas Gadjah Mada  
Yogyakarta, Indonesia  
johannesdedeodimasaryobimo@mail.ugm.ac.id

## Isi Repository

Yang akan tersedia di repository ini:

- Kode `.ipynb` untuk dua eksperimen (`with textbert` dan `imageonly`)
- `README`
- Laporan (`.pdf`)
