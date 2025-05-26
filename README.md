# 🚀 Tutorial Install Node Blockcast (Airdrop)

> 📅 Update Terakhir: Mei 2025  
> 🪙 Program: Airdrop Node Blockcast  
> 🌐 Website Pendaftaran: [https://app.blockcast.network/?referral-code=dxlJsG](https://app.blockcast.network/?referral-code=dxlJsG)

---

## 📋 Langkah-langkah Instalasi Node Blockcast

### 1. 🔧 Start Docker (Jika belum berjalan)
```bash
sudo systemctl start docker
```

### 2. 📥 Clone Repository Blockcast
```bash
git clone https://github.com/Blockcast/beacon-docker-compose.git
```

### 3. 📂 Masuk ke Direktori
```bash
cd beacon-docker-compose
```

### 4. 🚀 Jalankan Node dengan Docker Compose
```bash
docker compose up -d
```

### 5. ✅ Cek Status Container
```bash
docker compose ps
```

---

## 🔑 6. Ambil Hardware ID & Challenge Key

```bash
docker compose exec blockcastd blockcastd init
```

### 📌 Copy dan simpan:
- Hardware ID
- Challenge Key

---

## 📝 7. Daftarkan Node Anda

👉 Kunjungi:  
[https://app.blockcast.network/?referral-code=dxlJsG](https://app.blockcast.network/?referral-code=dxlJsG)

📥 Masukkan:
- Hardware ID
- Challenge Key

---

## 🧾 8. Cek Log Node (Opsional)

```bash
docker logs -f blockcastd
```

---

## ✅ Selesai!

Selamat! Node Blockcast Anda sudah aktif dan siap berpartisipasi dalam program airdrop.

---

## 📚 Referensi

- GitHub Repo: [Blockcast/beacon-docker-compose](https://github.com/Blockcast/beacon-docker-compose)
- Website: [https://app.blockcast.network](https://app.blockcast.network)
