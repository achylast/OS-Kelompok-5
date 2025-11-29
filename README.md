# **CPU Scheduling dengan Sorting dan Scheduling **

Proyek ini berisi implementasi tiga algoritma **CPU Scheduling** menggunakan bahasa **C**, yaitu:
- **FCFS (First Come First Served)**
- **SJF (Shortest Job First)**
- **Round Robin (RR)**

Setiap algoritma menggunakan metode **sorting** yang berbeda sesuai karakteristik penjadwalan:
| Algoritma Scheduling | Metode Sorting | Berdasarkan |
|---------------------|----------------|-------------|
| FCFS | Bubble Sort | Arrival Time (AT) |
| SJF | Quick Sort | Burst Time (BT) |
| Round Robin | Merge Sort | Arrival Time (AT) |

---

## **🎯 Tujuan Project**
- Mensimulasikan proses penjadwalan CPU pada sistem operasi.
- Menghitung waktu eksekusi proses dan metrik performa seperti:
  - Waiting Time (WT)
  - Turnaround Time (TAT)
  - Response Time (RT)
- Membandingkan efektivitas ketiga algoritma scheduling.

---

## **📌 Penjelasan Singkat**
### **Sorting**
Sorting digunakan untuk **menentukan urutan proses sebelum dijadwalkan**.  
Setiap algoritma butuh sorting yang berbeda sesuai kebutuhan:
- Bubble Sort mengurutkan proses berdasarkan waktu kedatangan (AT).
- Quick Sort mengurutkan berdasarkan lamanya waktu eksekusi (BT).
- Merge Sort menyusun proses berdasarkan AT untuk antrian Round Robin.

### **Scheduling**
Scheduling adalah proses **menjalankan simulasi eksekusi proses di CPU**, menghitung:
- Start Time
- Completion Time
- Waiting Time
- Turnaround Time
- Response Time

Setiap algoritma memiliki cara kerja berbeda:
- **FCFS** menjalankan proses sesuai urutan kedatangan.
- **SJF** menjalankan proses dengan waktu eksekusi paling pendek dulu.
- **Round Robin** memberi giliran eksekusi secara bergantian dengan **time quantum**.


