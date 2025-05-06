R2 Testnet Automation Bot
🚀 R2 Testnet Auto: Bot yang dirancang untuk mengotomatisasi tugas-tugas di R2 Testnet. Bot ini berinteraksi dengan ekosistem R2 dengan melakukan tindakan seperti persetujuan token, staking, swapping, dan menambah liquidity, berdasarkan kredensial dompet yang diberikan.

Fitur-Fitur Utama:
🔒 Verifikasi Identitas Wallet melalui API WalletConnect untuk memverifikasi identitas pengguna dan memastikan wallet yang digunakan valid.

📊 Integrasi Dashboard R2 Testnet untuk mengambil informasi tentang faucet dan data token di jaringan testnet.

🔁 Eksekusi Loop Otomatis untuk menjalankan proses secara terus-menerus (approve token, beli/swap, stake, dan add liquidity) dengan jeda waktu antar aksi.

⏱ Delay Antar Aksi untuk memastikan proses dilakukan dengan lancar dan menghindari spam pada jaringan.

🔐 Penanganan Private Key secara aman untuk berinteraksi dengan wallet tanpa mengungkapkan private key secara langsung.
## REGISTER
- https://r2.money?code=HWNIR

Cara Menggunakan:
```
git clone https://github.com/19seniman/r2-testnet.git
cd r2-testnet
---
aktifkan venv:
---
python3 -m venv r2-testnet
source r2-testnet/bin/activate
---
Instal dependensi yang dibutuhkan
---
pip install web3 requests rich
---
masukan private key di  nano pk.txt
Jalankan skrip:
```python bot.py
