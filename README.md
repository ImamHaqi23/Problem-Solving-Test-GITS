# Kompleksitas Waktu dan Ruang

## Kompleksitas Waktu

### 1. Iterasi Melalui String: `O(n)`

- Kode mengiterasi setiap karakter dalam string `s` sekali menggunakan `for...of` loop.
- Misalkan panjang string `s` adalah `n`, maka kompleksitas waktu dari loop ini adalah `O(n)`.

### 2. Operasi Stack: `O(1)`

- Operasi `push` dan `pop` pada stack memiliki kompleksitas waktu `O(1)` per operasi.
- Dalam kasus terburuk, setiap karakter dalam string akan menyebabkan satu operasi `push` dan satu operasi `pop`, sehingga total waktu untuk operasi stack tetap `O(n)`.

**Total kompleksitas waktu adalah `O(n)`**.

## Kompleksitas Ruang

### 1. Penggunaan Stack: `O(n)`

- Stack dapat menyimpan hingga `n` karakter dalam kasus terburuk (misalnya, semua karakter adalah tanda kurung pembuka tanpa pasangan).
- Oleh karena itu, kompleksitas ruang untuk stack adalah `O(n)`.

### 2. Penggunaan Memori Tambahan: `O(1)`

- Variabel `bracketPairs` adalah objek tetap yang menyimpan pasangan tanda kurung, sehingga memiliki kompleksitas ruang `O(1)`.

**Total kompleksitas ruang adalah `O(n)`**.

## Kesimpulan

Program ini efisien dalam hal waktu dan ruang, dengan kompleksitas waktu O(n) dan kompleksitas ruang O(n). Ini memastikan bahwa program dapat memeriksa keseimbangan tanda kurung dalam waktu linear relatif terhadap panjang string, dan hanya menggunakan ruang yang proporsional dengan panjang string.
