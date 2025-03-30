PyMacroRecorder-1.1.9.4 Linux (Ubuntu Setup)
doksli (dokumentasi asli) -> https://github.com/LOUDO56/PyMacroRecord
websli (website  asli) -> www.pymacrorecord.com/

- kenapa saya buat ini?
gak ada alasan apa apa sih hehehe soalnya setup di ubuntu lumanyan ribet jadi tak setup sekalian

- gimana setupnya bang? aku nggak paham
oke oke gini step stepnya

1. kalau dari dokumentasi asli itu  harus punya python - (kalau bisa yang terbaru / lts) https://www.python.org/downloads/
()[./assset/pippip.png]
2. download release nya juga... https://github.com/LOUDO56/PyMacroRecord/releases
3. hasil download-an di extract
---
4. kalau sesuai doksli itu di suruh masuk ke folder terus install requirements.txt
```bash
cd <PATH TO SOFTWARE FOLDER>
pip3 install -r requirements.txt
```
tapi kalau gitu malah error
()[./asset/env.png]

oleh karena itu gue pakai venv langsung di folder itu
```bash
virtualenv .
source bin/activate
```
5. https://www.pythonguis.com/installation/install-tkinter-linux/ -> install tkinker juga
6. masuk folder src trus jalankan main.py
```bash
cd src
python3 main.py
```
()[./asste/mainpy.png]

FINAL
()[asset/demo.webm]
SILAHKAN DICOBA COBA TAPI TADI KU COBA KOK TIDAK BISA YA HEHEHE




















