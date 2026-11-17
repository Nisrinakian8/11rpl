# Panduan Kontribusi — 11RPL

## Branch
- `main`: versi stabil; jangan push langsung.
- `dev`: integrasi pekerjaan sebelum rilis ke `main`.
- Fitur dikerjakan pada branch `feature/<nama-fitur>` dari `dev`.
- Perbaikan dikerjakan pada branch `fix/<nama-perbaikan>` dari `dev`.

## Format commit
Gunakan Conventional Commits: `<type>(<scope>): <ringkasan>`.

Contoh:
- `feat(auth): tambah halaman login`
- `fix(home): perbaiki navigasi`
- `docs(readme): perbarui petunjuk instalasi`
- `style(ui): rapikan tampilan tombol`
- `refactor(api): sederhanakan fungsi pengguna`
- `test(auth): tambah pengujian login`

Tipe: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`. Gunakan huruf kecil dan ringkasan singkat.

## Alur Pull Request
1. Buat branch kerja dari `dev`.
2. Lakukan perubahan dan commit sesuai format.
3. Push branch ke GitHub.
4. Buat PR dengan base `dev`, sertakan tujuan, ringkasan perubahan, dan hasil pengujian.
5. Minta guru/pemilik repository (`@rakanjay11-ux`) meninjau PR.
6. Perbaiki masukan reviewer dan tunggu persetujuan.
7. Merge ke `dev`. Saat siap rilis, buat PR `dev` → `main`.

Jangan merge PR yang masih memiliki konflik atau pemeriksaan yang gagal.
