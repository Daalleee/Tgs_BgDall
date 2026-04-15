Berikut penjelasan **kelebihan dan kekurangan model Boolean vs Vector Space (TF-IDF)** dengan gaya yang mudah kamu pakai untuk jawaban ujian 👇

---

# ✅ 1. MODEL BOOLEAN

## ✔️ Konsep

* Dokumen direpresentasikan sebagai **ada / tidak ada term (0 atau 1)**
* Query pakai operator:

  * AND
  * OR
  * NOT

---

## ✅ Kelebihan Boolean

1. **Sederhana**

   * Mudah dipahami dan diimplementasikan

2. **Cepat**

   * Tidak perlu perhitungan kompleks (tidak ada TF-IDF, cosine, dll)

3. **Kontrol tinggi**

   * User bisa spesifik:

     ```text
     gold AND delivery NOT silver
     ```

---

## ❌ Kekurangan Boolean

1. **Tidak ada ranking**

   * Hasil hanya:

     ```text
     relevan / tidak relevan
     ```
   * Tidak tahu mana yang paling bagus

2. **Kaku**

   * Harus cocok persis dengan query

3. **Sulit untuk user awam**

   * Harus paham AND, OR, NOT

4. **Tidak mempertimbangkan frekuensi kata**

   * Kata muncul 1x atau 100x dianggap sama

---

# ✅ 2. MODEL VECTOR SPACE (TF-IDF)

## ✔️ Konsep

* Dokumen & query diubah jadi **vektor angka**
* Menggunakan:

  * TF (Term Frequency)
  * IDF
  * Cosine Similarity

---

## ✅ Kelebihan Vector

1. **Ada ranking (ini paling penting 🔥)**

   * Hasil diurutkan:

     ```text
     paling relevan → paling tidak relevan
     ```

2. **Lebih fleksibel**

   * Tidak harus cocok 100%
   * Mirip pun masih bisa muncul

3. **Memperhatikan bobot kata**

   * Kata penting → nilai lebih tinggi

4. **Lebih realistis**

   * Mirip cara kerja search engine (Google, dll)

---

## ❌ Kekurangan Vector

1. **Lebih kompleks**

   * Harus hitung:

     * TF
     * IDF
     * Cosine similarity

2. **Lebih lambat**

   * Karena banyak perhitungan

3. **Butuh preprocessing**

   * stemming, stopword, dll

4. **Tidak paham makna (semantik)**

   * Hanya hitung angka, bukan arti kata

---

# ⚖️ PERBANDINGAN SINGKAT

| Aspek         | Boolean     | Vector Space   |
| ------------- | ----------- | -------------- |
| Representasi  | 0 / 1       | Angka (TF-IDF) |
| Ranking       | ❌ Tidak ada | ✅ Ada          |
| Fleksibilitas | ❌ Kaku      | ✅ Fleksibel    |
| Kompleksitas  | ✅ Sederhana | ❌ Kompleks     |
| Akurasi       | ❌ Rendah    | ✅ Lebih tinggi |

---

# 🧠 INTI JAWABAN (VERSI UJIAN SINGKAT)

Kalau kamu mau jawaban ringkas:

```text
Model Boolean sederhana dan cepat namun tidak memiliki ranking dan bersifat kaku. 
Sedangkan model Vector Space lebih kompleks tetapi mampu memberikan ranking, 
lebih fleksibel, dan menghasilkan pencarian yang lebih relevan.
```

---

Kalau kamu mau, saya bisa:

* bantu buat **jawaban versi paragraf rapi (siap copy ke laporan)**
* atau buat **contoh kasus perbandingan biar makin paham**

Tinggal bilang aja 👍
