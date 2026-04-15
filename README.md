1. MODEL BOOLEAN
✔️ Konsep
Dokumen direpresentasikan sebagai ada / tidak ada term (0 atau 1)
Query pakai operator:
AND
OR
NOT
✅ Kelebihan Boolean
Sederhana
Mudah dipahami dan diimplementasikan
Cepat
Tidak perlu perhitungan kompleks (tidak ada TF-IDF, cosine, dll)
Kontrol tinggi

User bisa spesifik:

gold AND delivery NOT silver
❌ Kekurangan Boolean
Tidak ada ranking

Hasil hanya:

relevan / tidak relevan
Tidak tahu mana yang paling bagus
Kaku
Harus cocok persis dengan query
Sulit untuk user awam
Harus paham AND, OR, NOT
Tidak mempertimbangkan frekuensi kata
Kata muncul 1x atau 100x dianggap sama
✅ 2. MODEL VECTOR SPACE (TF-IDF)
✔️ Konsep
Dokumen & query diubah jadi vektor angka
Menggunakan:
TF (Term Frequency)
IDF
Cosine Similarity
✅ Kelebihan Vector
Ada ranking (ini paling penting 🔥)

Hasil diurutkan:

paling relevan → paling tidak relevan
Lebih fleksibel
Tidak harus cocok 100%
Mirip pun masih bisa muncul
Memperhatikan bobot kata
Kata penting → nilai lebih tinggi
Lebih realistis
Mirip cara kerja search engine (Google, dll)
❌ Kekurangan Vector
Lebih kompleks
Harus hitung:
TF
IDF
Cosine similarity
Lebih lambat
Karena banyak perhitungan
Butuh preprocessing
stemming, stopword, dll
Tidak paham makna (semantik)
Hanya hitung angka, bukan arti kata
⚖️ PERBANDINGAN SINGKAT
Aspek	Boolean	Vector Space
Representasi	0 / 1	Angka (TF-IDF)
Ranking	❌ Tidak ada	✅ Ada
Fleksibilitas	❌ Kaku	✅ Fleksibel
Kompleksitas	✅ Sederhana	❌ Kompleks
Akurasi	❌ Rendah	✅ Lebih tinggi
🧠 INTI JAWABAN (VERSI UJIAN SINGKAT)

Kalau kamu mau jawaban ringkas:

Model Boolean sederhana dan cepat namun tidak memiliki ranking dan bersifat kaku. 
Sedangkan model Vector Space lebih kompleks tetapi mampu memberikan ranking, 
lebih fleksibel, dan menghasilkan pencarian yang lebih relevan.
