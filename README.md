## Step 1 : Run Requirements
Buat file bat dengan menggunakan notepad untuk menjalankan secara otomatis file requirement. Buka notepadnya, ketik :
```
@echo OFF
Title requirements
cd %~dp0
pip install -r requirements.txt %*
pause
```
Lalu save as nya jangan txt, tapi allfiles dan akhiran ekstensinya .bat
## Step 2 : Run streamlit_app
Sama seperti langkah diatas, buat file bat menggunakan notepad, ketik :
```
@echo OFF
Title streamlit
cd %~dp0
streamlit run streamlit_app.py %*
pause
```
## Step 3 : Maka akan terbuka browser
Isikan sitemap web nya, misal : https://www.guntursapta.com/sitemap.xml maka semua link nya akan ter-ekstrak
