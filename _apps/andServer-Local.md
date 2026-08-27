---
layout: default
name: "andServer - Local"
category: "Alat"
icon: "cpu"
version: "1.2"
status: "Stable"
file_size: "5 MB"
description: "Jalankan web server HTTP lokal untuk melihat file dan situs web di HP."
playstore_url: "https://play.google.com/store/apps/details?id=id.andtree.localserver"

privacy_detail: |
  Kebijakan Privasi ini menjelaskan bagaimana aplikasi **andServer - Lokal** (kami) mengelola data dan informasi pengguna saat menggunakan aplikasi Android kami.

  ### 1. Akses Penyimpanan & File Lokal
  Aplikasi ini membutuhkan izin akses ke direktori/folder penyimpanan yang Anda pilih secara eksplisit. Akses ini digunakan **hanya** untuk memfasilitasi pembuatan Web Server lokal (localhost) agar file HTML, dokumen, atau media dalam folder tersebut dapat diakses melalui browser di perangkat Anda.

  - Kami **tidak pernah** mengumpulkan, mengunggah, membagikan, atau menyimpan data file Anda ke server eksternal/pihak ketiga mana pun.
  - Seluruh pemrosesan web server terjadi sepenuhnya secara lokal di dalam perangkat Anda (`http://127.0.0.1`).

  ### 2. Layanan Latar Belakang (Foreground Service)
  Aplikasi ini menggunakan layanan latar belakang (*Foreground Service*) tipe `dataSync` untuk menjaga koneksi server HTTP tetap aktif dan stabil saat Anda meminimalkan aplikasi atau berpindah ke aplikasi lain. Layanan ini menampilkan notifikasi persisten dan akan langsung berhenti saat Anda menutup aplikasi secara penuh.

  ### 3. Layanan Pihak Ketiga & Iklan (Google AdMob)
  Aplikasi ini menggunakan layanan pihak ketiga dari **Google AdMob** untuk menampilkan iklan (seperti Iklan Dihadiahi/Rewarded Ads). Google AdMob dapat mengumpulkan data tertentu untuk penayangan iklan yang relevan dan analisis, seperti:

  - Pengenal Perangkat (Device Identifiers / Ad ID).
  - Data analitik anonim terkait tayangan dan interaksi iklan.
  - Alamat IP (untuk estimasi lokasi kasar/geografis).

  Untuk informasi lebih detail mengenai bagaimana Google mengelola data pengguna, silakan kunjungi [Kebijakan Privasi Google](https://google.com).

  ### 4. Keamanan Data
  Privasi dan keamanan data Anda adalah prioritas kami. Karena aplikasi tidak mengirimkan data file Anda ke internet, data pribadi Anda tetap aman berada di dalam penyimpanan lokal perangkat Anda.

  ### 5. Perubahan Kebijakan Privasi
  Kami dapat memperbarui Kebijakan Privasi ini dari waktu ke waktu. Setiap perubahan akan dipublikasikan di halaman ini dengan tanggal pembaruan terbaru.

  ### 6. Hubungi Kami
  Jika Anda memiliki pertanyaan tentang Kebijakan Privasi ini, Anda dapat menghubungi pengembang dengan berkomentar disini.
---

<div class="max-w-4xl mx-auto px-4 py-12">
  <div class="bg-white rounded-3xl p-8 border border-slate-200/80 shadow-sm">
    <div class="flex items-center gap-4 mb-6">
      <div class="w-16 h-16 rounded-2xl bg-slate-900 text-white flex items-center justify-center">
        <i data-lucide="{{ page.icon }}" class="w-8 h-8 text-emerald-400"></i>
      </div>
      <div>
        <span class="text-xs font-extrabold text-emerald-600 uppercase tracking-widest">{{ page.category }}</span>
        <h1 class="text-3xl font-black text-slate-900">{{ page.name }}</h1>
      </div>
    </div>
    
    <p class="text-slate-600 text-base mb-8">{{ page.description }}</p>

    <div class="prose max-w-none text-slate-700">
      <h2 class="text-xl font-bold text-slate-900 mb-2">Kebijakan Privasi</h2>
      <div class="bg-slate-50 p-4 rounded-xl border border-slate-100 mb-6">
        {{ page.privacy_detail | markdownify }}
      </div>
    </div>

    <div class="pt-6 border-t border-slate-100 flex justify-between items-center">
      <a href="{{ '/' | relative_url }}" class="text-xs font-bold text-slate-600 hover:text-emerald-600">&larr; Kembali ke Beranda</a>
      <a href="{{ page.playstore_url }}" target="_blank" rel="noopener" class="inline-flex items-center gap-2 text-xs font-extrabold text-white bg-slate-900 hover:bg-emerald-600 px-4 py-2.5 rounded-xl transition-all">
        Download di Play Store <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
      </a>
    </div>
  </div>
</div>
