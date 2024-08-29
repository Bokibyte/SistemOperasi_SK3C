# Instalasi OS - Linux

Halo, Saya akan membagikan cara instalasi Linux dengan list distro yang saya sediakan. disini juga ada tutorialnya. ini dibuat sebagai tugas dan juga untuk mempercantik github supaya tampak hijau wkwk.  

---

# Step Menginstall Linux

- [Instalasi OS - Linux](#instalasi-os---linux)
- [Step Menginstall Linux](#step-menginstall-linux)
- [Software untuk Virtual Machine](#software-untuk-virtual-machine)
    - [Perbandingan VMware dan VirtualBox](#perbandingan-vmware-dan-virtualbox)
- [Pemilihan Distro](#pemilihan-distro)
- [Membuat VM](#membuat-vm)

---

# Software untuk Virtual Machine

Kebanyakan orang memilih antara menggunakan vm atau dualboot. tetapi, lebih praktis dengan vm. Berikut rekomendasi software vm:

- [Virtual Box](https://www.virtualbox.org/)
- [VMware Workstation](https://blogs.vmware.com/workstation/2024/05/vmware-workstation-pro-now-available-free-for-personal-use.html)


> [!WARNING]
> Pastikan device anda memiliki spesifikasi cukup kuat dan CPU harus mendukung teknologi virtualisasi seperti Intel VT-x atau AMD-V. Untuk user celeron, i know how its pain.

### Perbandingan VMware dan VirtualBox

| Aspek                  | VMware                                | VirtualBox (VBox)                     |
|------------------------|---------------------------------------|---------------------------------------|
| **Performa**           | Umumnya lebih baik dalam hal kinerja, terutama dalam aplikasi berat atau server. | Baik untuk penggunaan umum, tapi performa bisa lebih rendah dibanding VMware pada beban berat. |
| **Kompatibilitas**     | Mendukung berbagai sistem operasi tamu, termasuk integrasi yang baik dengan Windows dan Linux. | Juga mendukung banyak OS tamu, tapi terkadang ada masalah kompatibilitas pada OS tertentu. |
| **User Interface**     | Antarmuka pengguna yang lebih polished dan profesional, terutama pada versi berbayar (Workstation Pro). | Antarmuka sederhana dan fungsional, cukup mudah digunakan untuk pengguna umum. |
| **Fitur**              | Fitur canggih seperti snapshot, cloning, dan integrasi dengan perangkat keras lebih baik pada versi berbayar. | Menyediakan banyak fitur dasar dan beberapa fitur canggih, tetapi dengan kemampuan yang lebih terbatas. |
| **Lisensi**            | VMware Workstation Player tersedia gratis untuk penggunaan pribadi; Workstation Pro berbayar. | Gratis dan open-source, mendukung pengguna pribadi dan komersial tanpa biaya tambahan. |
| **Virtualization**     | Mendukung virtualisasi hardware langsung (VT-x/AMD-V), dengan optimasi yang baik di versi berbayar. | Juga mendukung VT-x/AMD-V, tetapi optimasi bisa kurang efisien dibanding VMware. |
| **Dukungan Komunitas** | Komunitas besar, terutama untuk produk berbayar, dengan banyak dokumentasi dan dukungan resmi. | Komunitas yang sangat besar dan aktif, banyak forum dan dokumentasi tersedia. |
| **Pembaruan**          | Pembaruan reguler, terutama untuk versi berbayar dengan peningkatan performa dan fitur. | Pembaruan reguler, tetapi tidak secepat atau seintensif VMware. |
| **Integrasi Host**     | Integrasi yang baik dengan host OS, terutama pada versi Workstation Pro. | Integrasi yang baik dengan host, tetapi tidak sehalus VMware dalam beberapa kasus. |
| **Biaya**              | Versi berbayar memiliki biaya lisensi yang cukup tinggi, meskipun ada versi gratis dengan fitur terbatas. | Gratis, tanpa biaya lisensi, bahkan untuk penggunaan komersial. |

Selanjutnya, kita akan menggunakan VirtualBox sebagai vm.

# Pemilihan Distro

- 

Distro[^1] linux ada banyak, bisa dipilih sesuai kebutuhan. berikut beberapa listnya:

# Membuat VM

[^1]:Distro Linux adalah istilah yang merujuk pada distribusi sistem operasi berbasis Linux. Setiap distro terdiri dari kernel Linux yang merupakan inti dari sistem operasi, ditambah dengan koleksi perangkat lunak, manajer paket, antarmuka pengguna, dan utilitas lain yang dirancang untuk memenuhi kebutuhan tertentu atau audiens tertentu.