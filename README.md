# 🍔 Food Ordering CLI — Python Project

Sistem pemesanan makanan baris perintah sederhana yang ditulis dalam Python. Proyek ini dirancang untuk pemula yang ingin mempraktekkan konsep pemrograman dasar seperti input / output, loop, conditionals, penanganan file, dan struktur data sederhana hehehe
---

## 📌 Overview

Program ini memungkinkan pengguna untuk:

* Melihat daftar menu makanan
* Melakukan pemesanan
* Menghitung total harga pesanan
* Menyimpan riwayat ke file
* Melihat riwayat pesanan sebelumnya

Tidak ada solusi kode yang disediakan agar kamu bisa mengembangkan logikanya sendiri.

---

## 🔄 Program Flow

### **1. Main Menu**

Pengguna memilih salah satu opsi:

* Lihat Menu
* Buat Pesanan
* Lihat Riwayat
* Keluar

### **2. Lihat Menu**

Program menampilkan daftar makanan dan harga.

### **3. Buat Pesanan**

* Menampilkan menu
* Meminta nama makanan yang ingin dipesan
* Meminta jumlah
* Menghitung total harga
* Menampilkan ringkasan
* Menyimpan pesanan ke file (TXT/JSON)

### **4. Lihat Riwayat Pesanan**

Program membaca file dan menampilkan daftar pesanan yang pernah dibuat.

### **5. Keluar Program**

Aplikasi ditutup.

---

## 📁 Project Structure

```
food-ordering-cli/
│── main.py
│── menu_data.py          (opsional)
│── order_handler.py      (opsional)
│── history.txt / history.json
└── README.md
```

---

## 📘 Example Menu Format (Optional)

```
{
  "Nasi Goreng": 15000,
  "Ayam Geprek": 18000,
  "Mie Goreng": 12000,
  "Es Teh": 5000,
  "Es Jeruk": 6000
}
```

---

## 📘 Example Order History Format

**TXT Version:**

```
Nasi Goreng x2 = 30000
Es Teh x1 = 5000
Tanggal: 2025-11-14
```

**JSON Version:**

```
[
  {
    "makanan": "Nasi Goreng",
    "jumlah": 2,
    "total": 30000,
    "tanggal": "2025-11-14"
  }
]
```

---

## 🚀 How to Run

1. Install Python (3.10+)
2. Run program:

```
python main.py
```

---

## 🧩 Next Improvements

* Tambah fitur hapus/edit menu
* Tambah validasi input
* Gunakan JSON untuk penyimpanan lebih rapi
* Buat versi GUI menggunakan Tkinter

---

## 📜 License

Projek ini dapat menggunakan lisensi MIT (opsional). Jika ingin ditambahkan, beri tahu saya.

---

### maju lo py
