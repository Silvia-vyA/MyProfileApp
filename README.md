# 📱 MyProfileApp — PAM 4

Aplikasi profil mahasiswa sederhana yang dibuat menggunakan **Jetpack Compose Multiplatform**.  
tugas pada mata kuliah **Pengembangan Aplikasi Web (PAM)**.

---

## 👤 Identitas Mahasiswa

- **Nama:** Silvia  
- **NIM:** 123140133  
- **Kelas:** RB  

---

## 🚀 Fitur Aplikasi

### 1. Penerapan MVVM
- Menggunakan pola arsitektur **Model-View-ViewModel (MVVM)**
- Menggunakan **StateFlow** untuk mengelola state
- Membuat `ProfileViewModel` sebagai pengatur data dan logika
- Menggunakan `ProfileUiState` untuk menyimpan data UI

---

### 2. Fitur Edit Profile
- Tersedia form untuk mengubah:
  - Nama
  - Bio
- Menggunakan konsep **state hoisting** pada TextField
- Tombol **Save** untuk menyimpan perubahan ke ViewModel
- Tombol **Cancel** untuk membatalkan perubahan

---

### 3. Fitur Dark Mode
- Terdapat switch untuk mengubah mode terang dan gelap
- State disimpan di ViewModel
- Tampilan aplikasi menyesuaikan secara otomatis

---

### 4. Tampilan UI
- Dibuat menggunakan **Jetpack Compose**
- Menggunakan layout berbasis card
- Tampilan responsive dan bisa di-scroll
- Warna menyesuaikan antara light mode dan dark mode

---

## 🖼️ Tampilan Aplikasi

### Mode Terang
![Light Mode](composeApp/src/jvmMain/kotlin/org/example/project/my1.jpeg)
---

### Edit Profile
![Edit Profile](composeApp/src/jvmMain/kotlin/org/example/project/my2.jpeg)
---

### Setelah Diubah
![Updated Profile](composeApp/src/jvmMain/kotlin/org/example/project/my3.jpeg)
---

### Mode Gelap
![Dark Mode](composeApp/src/jvmMain/kotlin/org/example/project/my4.jpeg)
---


