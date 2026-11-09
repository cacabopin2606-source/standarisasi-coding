Markdown
# Standarisasi Coding Tugas Pengujian & Integrasi

## Deskripsi
Project latihan penerapan standar pengujian (AAA, FIRST) dan integrasi kode (GitHub Actions CI) pada modul Shopping Cart dan User.

## Teknologi
- Node.js v20
- Jest (testing)
- ESLint (linting)
- Prettier (formatting)
- GitHub Actions (CI)

## Cara Menjalankan
```bash
npm install
npm test
npm run test:coverage
npm run lint
npm run format:check
Coverage
Struktur
Plaintext
src/       -> source code
tests/     -> unit test
.github/   -> CI workflow
Author
Nama: Nadia Laela Anabella Kurnia

NIM: E41250932


---

### Cara Menaruhnya di VS Code:

<Steps>
<Step subtitle="Buka File" title="Buka README.md di VS Code">
Di sidebar VS Code sebelah kiri, klik file `README.md`[cite: 34].
</Step>

<Step subtitle="Tempel Kode" title="Hapus Isi Lama & Paste Kode Baru">
Tekan `Cmd + A` (di Mac) untuk menyeleksi seluruh teks lama di `README.md`, lalu tekan tombol `Delete` atau `Backspace`. Setelah kosong, langsung **Paste** (`Cmd + V`) kode di atas.
</Step>

<Step subtitle="Simpan File" title="Simpan Perubahan">
Tekan `Cmd + S` untuk menyimpan file `README.md`.
</Step>

<Step subtitle="Commit & Push" title="Kirim ke GitHub">
Jalankan perintah berikut di terminal VS Code-mu[cite: 36]:
```bash
git add README.md
git commit -m "docs: add complete README.md"
git push