# AI-Property-Agent

AI Property Insight Agent – Automated Data Analysis with Natural Language Query

Proyek ini adalah AI Agent berbasis Opal yang mampu melakukan analisis data properti secara otomatis menggunakan pertanyaan natural language.
Sistem ini dibuat untuk memungkinkan pengguna mendapatkan insight dari dataset pivot tanah/kawasan tanpa perlu melakukan perhitungan manual.

<img width="1117" height="608" alt="image" src="https://github.com/user-attachments/assets/a28fc274-e09b-4fae-ac63-8fa27f413374" />



Agent ini dapat:

mengenali wilayah/lingkungan (neighborhood) dari input user

melakukan filtering data berdasarkan kebutuhan

menghasilkan laporan eksekutif otomatis

🎯 Tujuan utama proyek:
Mengotomatiskan proses analisis data dari pivot table sehingga pengguna dapat langsung bertanya dalam bahasa manusia dan menerima laporan analitikal yang ringkas.

🚀 Fitur Utama
1. Natural Language Data Query

Pengguna cukup bertanya, contohnya:
- "Bagaimana harga rata-rata di Timber?"
- "Rekomendasikan lingkungan murah untuk investasi."

Agent akan mengekstraksi maksud dan mengolah data secara otomatis.

2. Automated Data Extraction (Node-Based Flow)

Workflow agent terdiri dari beberapa node:

- Node Input – menerima pertanyaan user
- Node Extractor – Agent mengenali nama lingkungan dari teks user
- Node Validation – Membersihkan output dari node extractor
- Node Generate Query – Node ini membangun parameter analisis
- Node Output – Output berupa laporan eksekutif

Semua berjalan otomatis tanpa campur tangan manual.

3. Pivot Data Integration

Dataset menggunakan pivot yang berisi:

- Row Labels (nama lingkungan)
- Average SalePrice
- Average OverallQual
- Average GarageCars

Data ini disimpan sebagai Opal Asset dan diakses di setiap analisa melalui template engine.

4. Automated Report Generation

AI menghasilkan:
- insight harga
- korelasi kualitas
- rekomendasi lingkungan
- analisis berdasarkan niat user (murah vs mahal)

Output dalam format laporan eksekutif 3–5 kalimat.


📊 Contoh Query & Output

Input
“Bagaimana tren harga di Timber?”

Output :

<img width="540" height="227" alt="image" src="https://github.com/user-attachments/assets/3ccdc681-c4fb-4b63-a593-3eafba35d209" />


Input
“Rekomendasikan area harga rendah untuk investasi pertama.”

Output :

<img width="556" height="339" alt="image" src="https://github.com/user-attachments/assets/0301fe1f-63ea-4a9f-a0ac-193203a8b3de" />


🛠️ Tech Stack
| Komponen  | Teknologi                          |
| --------- | ---------------------------------- |
| AI Model  | Opal AI (LLM)                      |
| Workflow  | Opal Node System                   |
| Data      | Pivot Table (Ames Housing Dataset) |
| Integrasi | Asset Template System              |
| Output    | Executive Summary Generator        |



🎯 Key Achievements (Portfolio Value)

- Mengembangkan AI agent end-to-end menggunakan workflow automation.
- Mengotomatisasi analisis pivot table berbasis pertanyaan natural language.
- Memperkenalkan sistem filtrasi AI untuk memahami:
    - niat user (budget rendah / tinggi)
    - filter kualitas
    - filter harga
    - fokus lingkungan tertentu
- Mengurangi kebutuhan analisis manual dengan laporan otomatis maksimal 5 kalimat.
- Membuat dokumentasi lengkap & struktur workflow layak portfolio.


🧑‍💻 Kontributor

Athif Tafrihan Achyar
