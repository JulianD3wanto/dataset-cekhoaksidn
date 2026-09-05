# Dataset Cek Hoaks Indonesia

Dataset ini berisi data berita hoaks dan bukan hoaks berbahasa Indonesia.

## Struktur Dataset

Repository ini berisi dua file utama:

- `fakedataset.csv` — kumpulan berita hoaks
- `truedataset.csv` — kumpulan berita bukan hoaks

## Format Kolom

Setiap file CSV memiliki kolom:

| Kolom | Deskripsi |
|---|---|
| `title` | Judul berita |
| `text` | Isi atau ringkasan berita |
| `subject` | Kategori atau subjek berita |
| `date` | Tanggal data |

## Label

| File | Label |
|---|---:|
| `fakedataset.csv` | Hoaks |
| `truedataset.csv` | Bukan Hoaks |

Untuk kebutuhan klasifikasi:

```text
Hoaks       = 1
Bukan Hoaks = 0
