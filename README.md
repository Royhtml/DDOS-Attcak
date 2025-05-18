<img src ="https://www.puskomedia.id/blog/wp-content/uploads/2024/09/pemulihan-pasca-serangan-ddos-langkah-langkah-mengembalikan-server-ke-kondisi-normal.jpg">

---

# 🛡️ DDoS (Distributed Denial of Service) Attack

## 📘 Apa Itu DDoS?

**DDoS (Distributed Denial of Service)** adalah serangan siber di mana pelaku mencoba membuat layanan online tidak tersedia dengan membanjiri server, jaringan, atau sistem dengan lalu lintas internet dalam jumlah besar dari berbagai sumber secara bersamaan.

Serangan ini dilakukan oleh banyak komputer atau perangkat yang telah dikompromi (dikenal sebagai **botnet**), dan digunakan secara terkoordinasi untuk menyerang satu target.

---

## ⚙️ Cara Kerja DDoS

1. **Infiltrasi Botnet**: Penyerang menginfeksi ribuan hingga jutaan perangkat (komputer, router, IoT) dengan malware.
2. **Koordinasi Serangan**: Semua perangkat yang terinfeksi dikendalikan dari pusat (Command & Control Server).
3. **Peluncuran Serangan**: Semua perangkat mengirimkan lalu lintas atau permintaan ke target secara bersamaan, membuat sistem target menjadi overload dan tidak merespons permintaan pengguna yang sah.

---

## 📂 Jenis-Jenis Serangan DDoS

| Jenis Serangan               | Penjelasan                                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------------------------- |
| **Volumetric Attack**        | Menggunakan volume data besar untuk membanjiri bandwidth jaringan. Contoh: UDP flood, ICMP flood. |
| **Protocol Attack**          | Menargetkan kelemahan pada protokol komunikasi. Contoh: SYN flood, Ping of Death.                 |
| **Application Layer Attack** | Menargetkan aplikasi atau layanan tertentu. Contoh: HTTP flood, Slowloris.                        |

---

## 💥 Bahaya DDoS

1. **Downtime Layanan**

   * Situs atau aplikasi tidak bisa diakses oleh pengguna.
   * Mengganggu operasi bisnis secara langsung.

2. **Kerugian Finansial**

   * Kehilangan pendapatan akibat layanan yang offline.
   * Biaya tambahan untuk mitigasi dan perbaikan.

3. **Kehilangan Kepercayaan Pengguna**

   * Pengguna dapat beralih ke kompetitor.
   * Mencoreng reputasi merek atau perusahaan.

4. **Peluang Eksploitasi Lain**

   * Saat sistem sibuk menangani DDoS, penyerang bisa melancarkan serangan lain (misal, penyusupan data).

5. **Penggunaan Sumber Daya**

   * Menyebabkan beban tinggi pada CPU, RAM, dan bandwidth.
   * Dapat merusak infrastruktur server.

6. **Serangan Berulang**

   * Beberapa pelaku melakukan DDoS berulang kali atau meminta "uang tebusan" agar serangan dihentikan (ransom DDoS).

---

## 🧩 Contoh Kasus Nyata

* **GitHub (2018)**: Mengalami serangan DDoS terbesar yang tercatat saat itu, mencapai 1.35 Tbps.
* **Dyn DNS (2016)**: Serangan DDoS besar menyebabkan situs-situs besar seperti Twitter, Netflix, dan Reddit menjadi tidak bisa diakses di wilayah Amerika.

---

## 🛡️ Cara Mitigasi dan Perlindungan

1. **Gunakan CDN dan layanan anti-DDoS seperti Cloudflare, Akamai, atau AWS Shield.**
2. **Terapkan firewall yang dikonfigurasi untuk mengenali pola serangan.**
3. **Gunakan sistem deteksi intrusi (IDS) dan monitoring lalu lintas secara real-time.**
4. **Lakukan rate limiting dan filtering terhadap IP mencurigakan.**
5. **Siapkan rencana mitigasi darurat jika terjadi serangan.**

---

## ❗ Penting untuk Diingat

> Melakukan serangan DDoS adalah **ilegal** dan dapat dikenakan sanksi hukum berat di berbagai negara. Dokumen ini hanya bertujuan untuk **edukasi dan kesadaran keamanan siber**, bukan untuk mendukung aktivitas berbahaya.

---

## 📚 Referensi

* [Cloudflare – What is a DDoS Attack?](https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/)
* [OWASP – DDoS Cheat Sheet](https://owasp.org/www-community/attacks/Denial_of_Service)
* [Wikipedia – Denial-of-service attack](https://en.wikipedia.org/wiki/Denial-of-service_attack)

---
