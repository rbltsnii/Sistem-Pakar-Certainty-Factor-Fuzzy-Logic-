# 🤖 Sistem Pakar: Certainty Factor & Fuzzy Logic
2306141_Rabiul Tsani Ghifarulhaq A


Repositori ini merupakan implementasi sistem pakar sederhana berbasis dua pendekatan kecerdasan buatan:
- **Certainty Factor (CF)**: Untuk diagnosa penyakit berdasarkan gejala.
- **Fuzzy Logic**: Untuk mengatur kecepatan kipas AC berdasarkan suhu dan kelembaban.

---

## 🧠 Metode yang Digunakan

### 1. Certainty Factor (CF)
Certainty Factor digunakan untuk menghitung tingkat keyakinan terhadap suatu penyakit berdasarkan bobot gejala dan pengetahuan pakar.

**Contoh Gejala:**
- Demam
- Batuk
- Pilek
- Nyeri otot, dll.

**Contoh Penyakit:**
- Flu
- Common Cold
- COVID-19, dll.

💡 *Semakin besar nilai CF, semakin besar kemungkinan diagnosa penyakit tersebut benar.*

---

### 2. Fuzzy Logic
Fuzzy Logic digunakan untuk mengatur kecepatan kipas AC secara dinamis berdasarkan suhu dan kelembaban ruangan.

**Variabel Input:**
- Suhu (`temperature`) → dingin, nyaman, panas
- Kelembaban (`humidity`) → kering, normal, lembab, **sangat lembab** (baru ditambahkan)

**Output:**
- Kecepatan Kipas → mati, rendah, sedang, tinggi, maksimal

🔁 *Fuzzy system mampu menyesuaikan kondisi tanpa logika biner (iya/tidak), memberikan fleksibilitas dalam pengambilan keputusan.*

---
