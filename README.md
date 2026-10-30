# Keyla-Hetrin<PE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio - Sistem Informasi</title>
    <!-- Tailwind CSS CDN untuk styling yang cepat dan modern -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased selection:bg-indigo-500 selection:text-white">

    <!-- Header / Navbar -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-slate-900/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
            <a href="#" class="text-xl font-bold tracking-wider text-indigo-400">Portofolio<span class="text-white">.</span></a>
            <nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-300">
                <a href="#about" class="hover:text-indigo-400 transition">Tentang</a>
                <a href="#skills" class="hover:text-indigo-400 transition">Minat & Keahlian</a>
                <a href="#contact" class="hover:text-indigo-400 transition">Kontak</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center justify-center pt-20 px-6 bg-gradient-to-b from-slate-900 via-slate-800 to-slate-900">
        <div class="max-w-4xl mx-auto text-center">
            <div class="inline-block mb-4 px-4 py-1.5 bg-indigo-500/10 border border-indigo-500/30 rounded-full text-indigo-400 text-sm font-medium">
                Mahasiswa Sistem Informasi
            </div>
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight mb-6">
                Halo, Saya Mahasiswa <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-cyan-400">Sistem Informasi</span>
            </h1>
            <p class="text-lg md:text-xl text-slate-300 max-w-2xl mx-auto mb-10 leading-relaxed">
                Berada di persimpangan antara dunia <strong>Teknologi</strong> dan <strong>Bisnis</strong>. Saat ini sedang mendalami bagaimana sistem informasi dapat mentransformasi proses bisnis menjadi lebih efisien dan bernilai tinggi.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#about" class="px-8 py-3 bg-indigo-600 hover:bg-indigo-500 text-white font-medium rounded-xl transition shadow-lg shadow-indigo-600/30">
                    Kenali Saya
                </a>
                <a href="#contact" class="px-8 py-3 bg-slate-800 hover:bg-slate-700 border border-slate-700 text-slate-200 font-medium rounded-xl transition">
                    Hubungi Saya
                </a>
            </div>
        </div>
    </section>

    <!-- About & Identity Section -->
    <section id="about" class="py-20 px-6 bg-slate-900 border-t border-slate-800">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold tracking-tight mb-3">Identitas & Latar Belakang</h2>
                <div class="w-16 h-1 bg-indigo-500 mx-auto rounded-full"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8 items-center bg-slate-800/50 border border-slate-700/50 rounded-2xl p-8 backdrop-blur-sm">
                <div>
                    <h3 class="text-xl font-semibold mb-4 text-indigo-300">Profil Akademik</h3>
                    <ul class="space-y-3 text-slate-300">
                        <li class="flex items-center gap-3">
                            <i class="fa-solid fa-users text-indigo-400 w-5"></i>
                            <span><strong>Kelompok:</strong> Kelompok 9</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <i class="fa-solid fa-id-card text-indigo-400 w-5"></i>
                            <span><strong>NIM:</strong> 26051214148</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <i class="fa-solid fa-graduation-cap text-indigo-400 w-5"></i>
                            <span><strong>Program Studi:</strong> Sistem Informasi</span>
                        </li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-4 text-indigo-300">Visi & Minat</h3>
                    <p class="text-slate-300 leading-relaxed text-sm md:text-base">
                        Saya memiliki ketertarikan besar pada dunia teknologi dan strategi bisnis. Fokus belajar saya mencakup pemahaman bagaimana merancang solusi berbasis sistem informasi yang solutif, inovatif, dan mampu menjawab kebutuhan dunia industri modern.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Minat & Keahlian (Tech & Business) -->
    <section id="skills" class="py-20 px-6 bg-slate-900/50">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold tracking-tight mb-3">Fokus & Ketertarikan</h2>
                <div class="w-16 h-1 bg-indigo-500 mx-auto rounded-full"></div>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- Teknologi Card -->
                <div class="bg-slate-800 border border-slate-700 p-8 rounded-2xl hover:border-indigo-500/50 transition">
                    <div class="w-12 h-12 bg-indigo-500/10 rounded-xl flex items-center justify-center text-indigo-400 text-xl mb-6">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Dunia Teknologi</h3>
                    <p class="text-slate-300 leading-relaxed text-sm md:text-base mb-4">
                        Mempelajari fondasi sistem informasi, basis data, pengembangan aplikasi, serta infrastruktur teknologi yang menjadi pendukung utama operasional digital masa kini.
                    </p>
                </div>

                <!-- Bisnis Card -->
                <div class="bg-slate-800 border border-slate-700 p-8 rounded-2xl hover:border-indigo-500/50 transition">
                    <div class="w-12 h-12 bg-cyan-500/10 rounded-xl flex items-center justify-center text-cyan-400 text-xl mb-6">
                        <i class="fa-solid fa-chart-line"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Dunia Bisnis</h3>
                    <p class="text-slate-300 leading-relaxed text-sm md:text-base mb-4">
                        Memahami analisis proses bisnis, manajemen sistem informasi perusahaan, serta bagaimana teknologi dapat memberikan keunggulan kompetitif (competitive advantage) bagi organisasi.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-6 bg-slate-900 border-t border-slate-800">
        <div class="max-w-2xl mx-auto text-center">
            <h2 class="text-3xl font-bold tracking-tight mb-4">Mari Terhubung</h2>
            <p class="text-slate-300 mb-8">
                Tertarik berkolaborasi atau ingin berdiskusi seputar teknologi dan sistem informasi? Jangan ragu untuk menghubungi saya.
            </p>
            <div class="inline-flex items-center gap-4 bg-slate-800 border border-slate-700 px-6 py-4 rounded-xl text-slate-200">
                <i class="fa-solid fa-envelope text-indigo-400 text-xl"></i>
                <span class="font-medium">NIM: 26051214148 (Kelompok 9)</span>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-slate-950 border-t border-slate-900 text-center text-sm text-slate-500">
        <p>&copy; 2026 - Portofolio Sistem Informasi. Dibuat dengan semangat belajar.</p>
    </footer>

</body>
</html>!DOCTY
