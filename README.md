# blank

Implementasi sederhana untuk membatasi crawling/indexing:

- `robots.txt` dengan `Disallow: /`
- `meta robots` di `index.html` dengan nilai:
  - `noindex`
  - `nofollow`
  - `noarchive`
  - `nosnippet`
  - `noimageindex`
- `404.html` sebagai fallback agar path/slug yang tidak ada tetap menampilkan halaman blank yang sama

Catatan: kepatuhan crawler terhadap instruksi ini bergantung pada kebijakan masing-masing layanan.