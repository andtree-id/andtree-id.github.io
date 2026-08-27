---
layout: default
name: "andBerkas"
category: "Alat"
icon: "cpu"
version: "1.2"
status: "Stable"
file_size: "11 MB"
description: "Pintasan cepat untuk membuka aplikasi Files bawaan sistem Android langsung"
playstore_url: "https://play.google.com/store/apps/details?id=id.andtree.berkas"

privacy_detail: |
  Kebijakan Privasi ini menjelaskan bagaimana aplikasi kami mengelola informasi Anda. Aplikasi ini dirancang sebagai alat bantu pintasan (shortcut) sederhana untuk membuka pengelola berkas sistem bawaan Android (DocumentsUI).

  ### 1. Pengumpulan dan Penggunaan Data
  Kami **tidak mengumpulkan, menyimpan, memproses, atau membagikan** data pribadi maupun informasi perangkat Anda dalam bentuk apa pun. Aplikasi ini bekerja sepenuhnya secara lokal pada perangkat Anda.

  ### 2. Izin Akses Penyimpanan
  Aplikasi ini mungkin memerlukan izin akses penyimpanan standar Android untuk mengarahkan Anda ke direktori utama (root storage). Kebijakan terkait akses berkas:
  
  - Aplikasi ini **tidak membaca, mengubah, mengunggah, atau menghapus** berkas pribadi Anda.
  - Semua aktivitas pengelolaan berkas dilakukan sepenuhnya oleh aplikasi sistem resmi Android (DocumentsUI), bukan oleh aplikasi ini.

  ### 3. Layanan Pihak Ketiga
  Aplikasi ini tidak menggunakan layanan pihak ketiga, SDK analitik, iklan, atau pelacak (trackers) yang mengumpulkan data pengguna.

  ### 4. Keamanan Data
  Karena kami tidak mengumpulkan data apa pun dari pengguna, tidak ada data pribadi Anda yang disimpan di server luar maupun lokal oleh aplikasi ini.

  ### 5. Perubahan Kebijakan Privasi
  Kami dapat memperbarui Kebijakan Privasi ini dari waktu ke waktu jika diperlukan. Setiap perubahan akan berlaku segera setelah diperbarui di halaman ini.

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
