# Stable Diffusion - Tugas (CelebA)

Repositori ini digunakan untuk tugas implementasi dan eksperimen model diffusion berbasis PyTorch menggunakan dataset **CelebA**.

## Isi Proyek

- `denoising_diffusion_pytorch/` : source code utama model diffusion
- `scripts/` : script training dan sampling (1D, 2D, dan CFG)
- `notebooks/` : notebook eksperimen
- `model-result/` : folder output hasil model

## Cara Menjalankan

1. Buat virtual environment (opsional, disarankan).
2. Install dependency:

```bash
pip install -e .
```

3. Jalankan training (contoh 2D):

```bash
python scripts/trainer_2d.py
```

4. Jalankan sampling (contoh 2D):

```bash
python scripts/sampler_2d.py
```

## Catatan

- Pastikan PyTorch sudah sesuai dengan CUDA/GPU yang digunakan.
- Hasil training dan gambar output dapat disimpan di folder `model-result/`.

## Hasil Terakhir

- Dataset: **CelebA**
- Hasil output terbaru di `model-result/`: **`sample.png`**
- Waktu file terakhir: **14 Mei 2026, 23:36**
