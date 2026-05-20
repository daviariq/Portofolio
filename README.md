# Portofolio — Davi Ariq

Portofolio pribadi (Data & Machine Learning), website statis satu file.

## Jalankan lokal
Cukup buka `index.html` di browser, atau:
```bash
npx serve .
```

## Deploy ke Vercel
1. Push folder ini ke sebuah repo GitHub (mis. `daviariq/portfolio`).
2. Buka https://vercel.com → **Add New → Project** → impor repo tersebut.
3. Framework Preset: **Other** (tidak perlu build command). Output: root folder.
4. Klik **Deploy**. Selesai — situs akan tayang di `namaproyek.vercel.app`.

Alternatif tercepat via terminal:
```bash
npm i -g vercel
vercel        # ikuti prompt, login, lalu deploy
vercel --prod # untuk versi produksi
```
