# PT. RAVIN JAYA KONSTRUKSI — Website Resmi

## Cara Deploy ke Vercel
1. Ekstrak file ZIP ini ke sebuah folder di komputer Anda.
2. **Setup Google Spreadsheet & Apps Script (Database Form Konsultasi):**
   - Buat Google Spreadsheet baru bernama `Database_PT_Ravin_Jaya_Konstruksi`.
   - Buat tab/sheet bernama `Konsultasi`.
   - Buka **Extensions > Apps Script**, tempel isi file `apps-script-code.gs`, lalu klik **Deploy > New deployment > Web app** (Execute as: *Me*, Who has access: *Anyone*).
   - Salin URL Web App yang dihasilkan, lalu tempel ke `GOOGLE_SCRIPT_URL` di dalam `assets/js/app.js`.
3. **Upload ke GitHub & Deploy ke Vercel:**
   - Upload seluruh isi folder ini ke repository baru di GitHub.
   - Login ke Vercel (`vercel.com`), klik **Add New > Project**, pilih repository tersebut, lalu klik **Deploy**.
