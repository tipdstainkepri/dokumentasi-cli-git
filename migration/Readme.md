# Migrasi dari Project lama ke GitHub terbaru

1. Hapus Remote project lama
```bash
git remote remove origin
```

2. Ambil link remote dari GitHub dan tambahkan remote
```bash
git remote add origin https://github.com/tipdstainsultanabdurrahmankepri/nama-repo.git
```

3. Sync repo lokal dengan GitHub
```bash
git push --all origin
```