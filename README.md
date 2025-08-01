<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SBM GROUP - Dari Bisnis Biasa Jadi Luar Biasa</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Poppins -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Custom Styles */
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8f9fa; /* Light gray background */
        }
        
        /* Custom Yellow Color */
        .bg-brand-yellow { background-color: #FFD700; }
        .text-brand-yellow { color: #FFD700; }
        .border-brand-yellow { border-color: #FFD700; }

        /* Smooth scroll behavior */
        html {
            scroll-behavior: smooth;
        }

        /* Simple animation for elements */
        .reveal {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }
        
        /* Testimonial Carousel Styles */
        .carousel-container {
            overflow: hidden;
            position: relative;
        }
        .carousel-track {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }
        .carousel-slide {
            min-width: 100%;
            box-sizing: border-box;
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Container Utama -->
    <div class="max-w-4xl mx-auto">

        <!-- ===== BAGIAN 1: BERANDA & OWNER HIGHLIGHT ===== -->
        <section id="beranda" class="relative text-center min-h-screen flex flex-col justify-center items-center p-6 bg-white shadow-lg rounded-b-3xl overflow-hidden">
            <!-- Owner Image -->
            <div class="absolute -bottom-12 sm:-bottom-20 left-1/2 -translate-x-1/2 w-64 h-64 sm:w-80 sm:h-80 opacity-10 z-0">
                 <img src="https://placehold.co/400x400/FFFFFF/FFFFFF?text=+" alt="Decorative Graphic" class="w-full h-full">
            </div>
            
            <div class="relative z-10">
                <img src="https://placehold.co/150x150/FFD700/000000?text=Mas+Alaah" alt="Mas Alaah - Owner SBM GROUP" class="w-32 h-32 md:w-40 md:h-40 mx-auto rounded-full object-cover border-4 border-brand-yellow shadow-xl mb-4">
                <h2 class="text-2xl font-bold">Mas Alaah</h2>
                <p class="text-gray-500 mb-6">Owner SBM GROUP</p>

                <h1 class="text-3xl md:text-5xl font-extrabold mb-3 reveal">Kenalan Sama <span class="text-brand-yellow">SBM GROUP</span></h1>
                <p class="max-w-2xl mx-auto text-gray-600 mb-8 reveal">
                    “Dari Bisnis yang Dipikir Ga Laku, Jadi Punya Banyak Cabang & Karyawan!”
                </p>

                <div class="flex flex-col sm:flex-row gap-4 justify-center reveal">
                    <a href="#mitra" class="bg-brand-yellow text-black font-bold py-3 px-8 rounded-full shadow-lg hover:bg-yellow-400 transition duration-300">
                        Gabung Jadi Mitra
                    </a>
                    <a href="#produk" class="bg-gray-800 text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-700 transition duration-300">
                        Lihat Produk Kami
                    </a>
                </div>
            </div>
        </section>

        <!-- ===== BAGIAN 2: PRODUK & LAYANAN ===== -->
        <section id="produk" class="py-20 px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-extrabold reveal">Produk & Layanan Kami</h2>
                <p class="text-gray-500 mt-2 reveal">Berbagai peluang bisnis yang sudah terbukti menghasilkan.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Produk 1: Mitra Agen Bank -->
                <div class="bg-white p-6 rounded-2xl shadow-lg text-center reveal hover:scale-105 transition-transform duration-300">
                    <div class="text-5xl text-brand-yellow mb-4"><i class="fas fa-university"></i></div>
                    <h3 class="text-xl font-bold mb-2">Mitra Agen Bank</h3>
                    <p class="text-gray-600 text-sm">Jadi agen bank resmi tanpa sewa ruko & tanpa karyawan. Transaksi mudah, komisi melimpah.</p>
                </div>

                <!-- Produk 2: Laundry Harian -->
                <div class="bg-white p-6 rounded-2xl shadow-lg text-center reveal hover:scale-105 transition-transform duration-300">
                    <div class="text-5xl text-brand-yellow mb-4"><i class="fas fa-tshirt"></i></div>
                    <h3 class="text-xl font-bold mb-2">Laundry Harian</h3>
                    <p class="text-gray-600 text-sm">Bisnis laundry kiloan dengan sistem modern yang anti ribet dan selalu dibutuhkan.</p>
                </div>

                <!-- Produk 3: Parfum Isi Ulang -->
                <div class="bg-white p-6 rounded-2xl shadow-lg text-center reveal hover:scale-105 transition-transform duration-300">
                    <div class="text-5xl text-brand-yellow mb-4"><i class="fas fa-spray-can-sparkles"></i></div>
                    <h3 class="text-xl font-bold mb-2">Parfum Isi Ulang</h3>
                    <p class="text-gray-600 text-sm">Jual parfum berkualitas dengan aroma tahan lama dan keuntungan menjanjikan.</p>
                </div>

                <!-- Produk 4: Warkop Modern -->
                <div class="bg-white p-6 rounded-2xl shadow-lg text-center reveal hover:scale-105 transition-transform duration-300">
                    <div class="text-5xl text-brand-yellow mb-4"><i class="fas fa-coffee"></i></div>
                    <h3 class="text-xl font-bold mb-2">Warkop Modern</h3>
                    <p class="text-gray-600 text-sm">Konsep warung kopi kekinian yang jadi tempat nongkrong favorit anak muda.</p>
                </div>
                
                <!-- Produk 5: GTS (Teknologi) -->
                <div class="bg-white p-6 rounded-2xl shadow-lg text-center md:col-span-2 lg:col-span-1 reveal hover:scale-105 transition-transform duration-300">
                    <div class="text-5xl text-brand-yellow mb-4"><i class="fas fa-laptop-code"></i></div>
                    <h3 class="text-xl font-bold mb-2">GTS Teknologi</h3>
                    <p class="text-gray-600 text-sm mb-4">Jasa pembuatan aplikasi, website, dan solusi teknologi untuk bisnis Anda.</p>
                    <a href="https://mitragts.co.id" target="_blank" class="text-sm font-semibold text-blue-600 hover:underline">Kunjungi mitragts.co.id <i class="fas fa-external-link-alt ml-1"></i></a>
                </div>
            </div>
        </section>

        <!-- ===== BAGIAN 3: TESTIMONI & SOCIAL PROOF ===== -->
        <section id="testimoni" class="py-20 px-6 bg-gray-800 text-white">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-extrabold reveal">Apa Kata Mereka?</h2>
                <p class="text-gray-300 mt-2 reveal">Kisah sukses dari para mitra yang telah bergabung.</p>
            </div>
            
            <!-- Testimonial Carousel -->
            <div class="carousel-container max-w-2xl mx-auto bg-gray-700 rounded-2xl p-8 shadow-2xl reveal">
                <div class="carousel-track">
                    <!-- Slide 1 -->
                    <div class="carousel-slide px-4 text-center">
                        <p class="italic mb-4">"Alhamdulillah, setelah gabung jadi agen bank SBM, penghasilan saya naik 2x lipat. Modalnya kecil, untungnya besar!"</p>
                        <p class="font-bold text-brand-yellow">- Ibu Siti, Mitra Agen Bank</p>
                    </div>
                    <!-- Slide 2 -->
                    <div class="carousel-slide px-4 text-center">
                        <p class="italic mb-4">"Laundry saya sekarang jadi rujukan di komplek. Sistem dari SBM Group bener-bener bantu banget buat manajemen."</p>
                        <p class="font-bold text-brand-yellow">- Pak Budi, Mitra Laundry</p>
                    </div>
                    <!-- Slide 3 -->
                    <div class="carousel-slide px-4 text-center">
                        <p class="italic mb-4">"Awalnya ragu, tapi ternyata bisnis parfum ini laku keras. Terima kasih SBM Group atas bimbingannya."</p>
                        <p class="font-bold text-brand-yellow">- Mas Andi, Mitra Parfum</p>
                    </div>
                </div>
                 <div class="flex justify-center mt-6 space-x-2">
                    <button class="carousel-prev bg-brand-yellow text-black h-8 w-8 rounded-full font-bold hover:bg-yellow-400">&lt;</button>
                    <button class="carousel-next bg-brand-yellow text-black h-8 w-8 rounded-full font-bold hover:bg-yellow-400">&gt;</button>
                </div>
            </div>

            <div class="mt-12 text-center grid grid-cols-2 md:grid-cols-4 gap-8 max-w-3xl mx-auto reveal">
                <div>
                    <p class="text-4xl font-extrabold text-brand-yellow">500+</p>
                    <p class="text-gray-300">Mitra Terdaftar</p>
                </div>
                <div>
                    <p class="text-4xl font-extrabold text-brand-yellow">100+</p>
                    <p class="text-gray-300">Cabang Usaha</p>
                </div>
                <div>
                    <p class="text-4xl font-extrabold text-brand-yellow">250+</p>
                    <p class="text-gray-300">Karyawan</p>
                </div>
                 <div>
                    <p class="text-4xl font-extrabold text-brand-yellow">5+</p>
                    <p class="text-gray-300">Unit Bisnis</p>
                </div>
            </div>
        </section>

        <!-- ===== BAGIAN 4: HUBUNGI KAMI & GABUNG MITRA ===== -->
        <section id="mitra" class="py-20 px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-extrabold reveal">Siap Sukses Bersama Kami?</h2>
                <p class="text-gray-500 mt-2 reveal">Isi form di bawah atau scan QR code untuk langsung terhubung!</p>
            </div>

            <div class="grid md:grid-cols-2 gap-10 items-center max-w-4xl mx-auto">
                <!-- Form Pendaftaran -->
                <div class="bg-white p-8 rounded-2xl shadow-lg reveal">
                    <div id="mitraForm">
                        <div class="mb-4">
                            <label for="nama" class="block text-sm font-bold mb-2">Nama Lengkap</label>
                            <input type="text" id="nama" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-yellow" placeholder="Masukkan nama Anda">
                        </div>
                        <div class="mb-4">
                            <label for="wa" class="block text-sm font-bold mb-2">Nomor WhatsApp</label>
                            <input type="tel" id="wa" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-yellow" placeholder="Contoh: 08123456789">
                        </div>
                        <div class="mb-6">
                            <label for="minat" class="block text-sm font-bold mb-2">Minat Kemitraan</label>
                            <select id="minat" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-yellow">
                                <option>Pilih Minat Bisnis</option>
                                <option>Mitra Agen Bank</option>
                                <option>Laundry Harian</option>
                                <option>Parfum Isi Ulang</option>
                                <option>Warkop Modern</option>
                            </select>
                        </div>
                        <button type="button" id="submitButton" class="w-full bg-brand-yellow text-black font-bold py-3 px-8 rounded-full shadow-lg hover:bg-yellow-400 transition duration-300">
                            Kirim & Daftar Sekarang
                        </button>
                    </div>
                </div>

                <!-- QR Code & Kontak Lain -->
                <div class="text-center reveal">
                    <h3 class="font-bold text-lg mb-4">Atau Scan QR Code Ini!</h3>
                    <div class="flex justify-center mb-6">
                         <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://wa.me/628881123222?text=Halo%20SBM%20Group,%20saya%20tertarik%20untuk%20bergabung%20menjadi%20mitra." alt="QR Code Pendaftaran Mitra" class="rounded-lg shadow-md">
                    </div>
                    <a href="https://wa.me/628881123222?text=Halo%20SBM%20Group,%20saya%20tertarik%20untuk%20bergabung%20menjadi%20mitra." target="_blank" class="inline-block bg-green-500 text-white font-bold py-3 px-6 rounded-full shadow-lg hover:bg-green-600 transition duration-300">
                        <i class="fab fa-whatsapp mr-2"></i> Hubungi via WhatsApp
                    </a>
                    
                    <div class="mt-8">
                        <p class="font-bold mb-3">Temukan Kami di:</p>
                        <div class="flex justify-center gap-6 text-2xl">
                            <a href="https://www.instagram.com/mas_alahh?igsh=ZGQ2Z3RnNGgxa21q" target="_blank" class="text-gray-500 hover:text-brand-yellow"><i class="fab fa-instagram"></i></a>
                            <a href="https://www.tiktok.com/@mas.alahh?_t=ZS-8yWKUByJD2F&_r=1" target="_blank" class="text-gray-500 hover:text-brand-yellow"><i class="fab fa-tiktok"></i></a>
                            <a href="#" class="text-gray-500 hover:text-brand-yellow"><i class="fab fa-youtube"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center py-6 text-sm text-gray-500">
            <p>&copy; 2025 SBM GROUP. All Rights Reserved.</p>
        </footer>

    </div>

    <!-- Modal for alerts -->
    <div id="alertModal" class="fixed inset-0 bg-black bg-opacity-50 flex justify-center items-center z-50 hidden">
        <div class="bg-white p-8 rounded-2xl shadow-xl text-center max-w-sm mx-4">
            <p id="alertMessage" class="mb-6 text-gray-700">Pesan Anda di sini.</p>
            <button id="closeModal" class="bg-brand-yellow text-black font-bold py-2 px-8 rounded-full">OK</button>
        </div>
    </div>


    <script>
    document.addEventListener('DOMContentLoaded', function () {
        // Animation on Scroll
        const revealElements = document.querySelectorAll('.reveal');
        const revealOnScroll = () => {
            const windowHeight = window.innerHeight;
            revealElements.forEach(el => {
                const elementTop = el.getBoundingClientRect().top;
                if (elementTop < windowHeight - 50) {
                    el.classList.add('active');
                }
            });
        };
        window.addEventListener('scroll', revealOnScroll);
        revealOnScroll(); // Initial check

        // Testimonial Carousel
        const track = document.querySelector('.carousel-track');
        const slides = Array.from(track.children);
        const nextButton = document.querySelector('.carousel-next');
        const prevButton = document.querySelector('.carousel-prev');
        let currentIndex = 0;

        const updateSlidePosition = () => {
            track.style.transform = 'translateX(-' + (currentIndex * 100) + '%)';
        };

        nextButton.addEventListener('click', () => {
            currentIndex = (currentIndex + 1) % slides.length;
            updateSlidePosition();
        });

        prevButton.addEventListener('click', () => {
            currentIndex = (currentIndex - 1 + slides.length) % slides.length;
            updateSlidePosition();
        });
        
        // Auto-play carousel
        setInterval(() => {
            currentIndex = (currentIndex + 1) % slides.length;
            updateSlidePosition();
        }, 5000); // Change slide every 5 seconds

        // Form submission to WhatsApp
        const submitButton = document.getElementById('submitButton');
        const alertModal = document.getElementById('alertModal');
        const alertMessage = document.getElementById('alertMessage');
        const closeModal = document.getElementById('closeModal');

        const showAlert = (message) => {
            alertMessage.textContent = message;
            alertModal.classList.remove('hidden');
        };

        closeModal.addEventListener('click', () => {
            alertModal.classList.add('hidden');
        });

        submitButton.addEventListener('click', () => {
            const nama = document.getElementById('nama').value.trim();
            const wa = document.getElementById('wa').value.trim();
            const minat = document.getElementById('minat').value;

            if (!nama || !wa || minat === "Pilih Minat Bisnis") {
                showAlert('Mohon lengkapi semua data (Nama, WhatsApp, dan Minat Bisnis) sebelum mengirim.');
                return;
            }

            const message = `Halo SBM Group, saya ingin mendaftar sebagai mitra.\n\nNama: ${nama}\nNomor WA: ${wa}\nMinat Bisnis: ${minat}`;
            const encodedMessage = encodeURIComponent(message);
            const waNumber = '628881123222';
            const waUrl = `https://wa.me/${waNumber}?text=${encodedMessage}`;

            window.open(waUrl, '_blank');
        });
    });
    </script>
</body>
</html>
