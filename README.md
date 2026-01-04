# 0/1 Knapsack Problem - Dynamic Programming

## 📋 Informasi Tugas

**Mata Kuliah:** Desain dan Analisis Algoritma  
**Dosen Pengampu:** Ibu Desi Anggreani, S.Kom.,MT.  
**Topik:** 0/1 Knapsack Problem dengan Dynamic Programming  

---

## 👤 Identitas Mahasiswa

**Nama:** Fathya Shabira A.T   
**NIM:** 105841111923  
**Kelas:** 5D  

---

## 📖 Deskripsi

Implementasi algoritma Dynamic Programming untuk menyelesaikan 
0/1 Knapsack Problem dalam optimasi muatan truk wingbox.

Kasus: Memaksimalkan berat total muatan truk dengan kapasitas 
terbatas (25 kg) dari 10 jenis item yang tersedia.

---

## 📊 Data

- **Jumlah Item:** 10 jenis muatan
- **Kapasitas Truk:** 25 kg
- **Metode:** Dynamic Programming (Bottom-Up Approach)

### Item yang Tersedia:
1. Beras (4.0 kg)
2. Semen (5.0 kg)
3. Baja Ringan (3.5 kg)
4. Kayu Olahan (6.0 kg)
5. Pupuk (4.2 kg)
6. Gula (3.8 kg)
7. Minyak Goreng (2.5 kg)
8. Kertas (3.0 kg)
9. Mesin Kecil (5.5 kg)
10. Plastik Industri (2.0 kg)

---

## ✅ Hasil

- **Total Berat Maksimal:** 25.0 kg (100% utilisasi)
- **Item Terpilih:** 6 dari 10 item
- **Kompleksitas Waktu:** O(n × W) = O(250) operasi
- **Kompleksitas Ruang:** O(n × W)

### Item yang Dimuat:
1. Semen (5.0 kg)
2. Baja Ringan (3.5 kg)
3. Kayu Olahan (6.0 kg)
4. Pupuk (4.2 kg)
5. Gula (3.8 kg)
6. Minyak Goreng (2.5 kg)

**Total: 25.0 kg**

---

## 🚀 Cara Menjalankan

### Prerequisites
- Python 3.x

### Eksekusi Program
```bash
python knapsack_fixed.py
