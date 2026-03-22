# 📱 MyProfileApp — PAM 4

Aplikasi profil mahasiswa sederhana yang dibuat menggunakan **Jetpack Compose Multiplatform** sebagai tugas pada mata kuliah **Pengembangan Aplikasi Web (PAM)**.

---

## 👤 Identitas Mahasiswa

- **Nama:** Silvia
- **NIM:** 123140133
- **Kelas:** RB

---

## ✨ Fitur Aplikasi

### 1. 🧩 Penerapan MVVM
- Menggunakan pola arsitektur **Model-View-ViewModel (MVVM)**
- Menggunakan **StateFlow** untuk mengelola state
- Membuat `ProfileViewModel` sebagai pengatur data dan logika aplikasi
- Menggunakan `ProfileUiState` untuk menyimpan data tampilan

### 2. ✏️ Fitur Edit Profile
- Tersedia form untuk mengubah:
  - Nama
  - Bio
- Menggunakan konsep **state hoisting** pada `TextField`
- Tombol **Save** untuk menyimpan perubahan ke ViewModel
- Tombol **Cancel** untuk membatalkan perubahan

### 3. 🌙 Fitur Dark Mode
- Terdapat switch untuk mengubah **mode terang** dan **mode gelap**
- State tema disimpan di ViewModel
- Tampilan aplikasi menyesuaikan secara otomatis sesuai mode yang dipilih

### 4. 🎨 Tampilan UI
- Dibuat menggunakan **Jetpack Compose**
- Menggunakan layout berbasis card
- Tampilan responsif dan dapat di-scroll
- Warna menyesuaikan antara **light mode** dan **dark mode**

---


## 🖼️ Tampilan Aplikasi

<p align="center">
  <img src="composeApp/src/jvmMain/kotlin/org/example/project/my1.jpeg" alt="Mode Terang" width="45%" />
  <img src="composeApp/src/jvmMain/kotlin/org/example/project/my2.jpeg" alt="Edit Profile" width="45%" />
</p>

<p align="center">
  <img src="composeApp/src/jvmMain/kotlin/org/example/project/my3.jpeg" alt="Setelah Diubah" width="45%" />
  <img src="composeApp/src/jvmMain/kotlin/org/example/project/my4.jpeg" alt="Mode Gelap" width="45%" />
</p>

<p align="center">
  <b>Mode Terang</b> &nbsp; | &nbsp; <b>Edit Profile</b> &nbsp; | &nbsp; <b>Setelah Diubah</b> &nbsp; | &nbsp; <b>Mode Gelap</b>
</p>

---


