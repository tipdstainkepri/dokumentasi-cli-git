# hapus cache .gitignore
**.gitignore** adalah file teks yang digunakan oleh Git untuk menentukan file atau direktori yang harus diabaikan atau tidak dilacak oleh sistem kontrol versi. File ini membantu menjaga repositori Git tetap bersih dan tidak berisi file yang tidak perlu. 
contoh penggunaan

```
# Ignore Mac system files
.DS_store

# Ignore node_modules folder
node_modules

# Ignore all text files
*.txt

# Ignore files related to API keys
.env

# Ignore SASS config files
.sass-cache
```


Terkadang ketika membuat file gitignore, file tersebut tidak berfungsi mengabaikan, jika hal tersebut terjadi kamu bisa ikuti langkah-langkah di bawah ini

1. Ketik Perintah Dibawah ini
```bash
git rm -rf --cached .
```

2. lalu kemudian ketik
```bash
git add .
```

3. commit perubahan yang dilakukan
```bash
git commit -m ".gitignore bekerja!"
```