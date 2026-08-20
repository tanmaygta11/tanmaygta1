# tanmaygta1
LAW FIRM
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A A Gaikwad & Associates | Law & Audit Firm</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            800: '#0f172a',
                            900: '#0b0f19',
                        },
                        gold: {
                            500: '#d4af37',
                            600: '#b89728',
                        }
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-navy-900 text-gray-100 font-sans antialiased">

    <!-- Navigation Bar -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-navy-900/90 backdrop-blur-md border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <i class="fa-solid fa-scale-balanced text-gold-500 text-2xl"></i>
                <div class="leading-tight">
                    <span class="text-base md:text-lg font-bold tracking-wider text-white block">A A GAIKWAD</span>
                    <span class="text-xs text-gold-500 tracking-widest font-semibold uppercase">& ASSOCIATES</span>
                </div>
            </div>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                <a href="#services" class="hover:text-gold-500 transition">Services</a>
                <a href="#about" class="hover:text-gold-500 transition">About Us</a>
                <a href="#contact" class="hover:text-gold-500 transition">Contact</a>
                <a href="tel:9850085712" class="flex items-center space-x-2 px-4 py-2 rounded bg-gold-500 text-navy-900 font-semibold hover:bg-gold-600 transition">
                    <i class="fa-solid fa-phone"></i>
                    <span>9850085712</span>
                </a>
            </nav>
            <button id="menu-btn" class="md:hidden text-2xl text-gray-300 focus:outline-none">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pt-2 pb-6 bg-navy-900 border-b border-gray-800">
            <a href="#services" class="block py-2 text-gray-300 hover:text-gold-500">Services</a>
            <a href="#about" class="block py-2 text-gray-300 hover:text-gold-500">About Us</a>
            <a href="#contact" class="block py-2 text-gray-300 hover:text-gold-500">Contact</a>
            <a href="tel:9850085712" class="block mt-4 text-center px-5 py-2.5 rounded bg-gold-500 text-navy-900 font-semibold">
                <i class="fa-solid fa-phone mr-2"></i> Call 9850085712
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative pt-32 pb-20 md:pt-48 md:pb-32 flex items-center justify-center bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-navy-800 via-navy-900 to-navy-900">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <span class="text-gold-500 font-semibold uppercase tracking-widest text-xs md:text-sm bg-gold-500/10 px-4 py-1.5 rounded-full border border-gold-500/20">Professional Legal & Auditing Services</span>
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight text-white mt-6 mb-6">
                A A GAIKWAD & ASSOCIATES
            </h1>
            <p class="max-w-2xl mx-auto text-gray-400 text-lg md:text-xl mb-10">
                Delivering rigorous legal counsel, financial auditing, and corporate compliance solutions from Virar West.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#contact" class="px-8 py-3.5 rounded bg-gold-500 text-navy-900 font-bold hover:bg-gold-600 transition shadow-lg shadow-gold-500/10">Schedule a Consultation</a>
                <a href="tel:9850085712" class="px-8 py-3.5 rounded border border-gray-700 hover:border-gold-500 text-gray-300 hover:text-gold-500 transition flex items-center justify-center space-x-2">
                    <i class="fa-solid fa-phone text-gold-500"></i>
                    <span>Call Now</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-24 bg-navy-800/50 border-t border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-gold-500 font-semibold tracking-wide uppercase text-sm mb-2">Our Practice Areas</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-white">Comprehensive Legal & Audit Solutions</h3>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-navy-900 p-8 rounded-lg border border-gray-800 hover:border-gold-500/50 transition group">
                    <div class="w-12 h-12 rounded bg-gold-500/10 flex items-center justify-center text-gold-500 text-xl mb-6 group-hover:bg-gold-500 group-hover:text-navy-900 transition">
                        <i class="fa-solid fa-gavel"></i>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-3">Legal & Advisory Services</h4>
                    <p class="text-gray-400 text-sm leading-relaxed">Strategic guidance on corporate matters, documentation, dispute resolution, and regulatory frameworks.</p>
                </div>
                <!-- Service 2 -->
                <div class="bg-navy-900 p-8 rounded-lg border border-gray-800 hover:border-gold-500/50 transition group">
                    <div class="w-12 h-12 rounded bg-gold-500/10 flex items-center justify-center text-gold-500 text-xl mb-6 group-hover:bg-gold-500 group-hover:text-navy-900 transition">
                        <i class="fa-solid fa-calculator"></i>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-3">Auditing & Assurance</h4>
                    <p class="text-gray-400 text-sm leading-relaxed">Statutory audits, internal financial controls review, risk assessments, and accounting compliance.</p>
                </div>
                <!-- Service 3 -->
                <div class="bg-navy-900 p-8 rounded-lg border border-gray-800 hover:border-gold-500/50 transition group">
                    <div class="w-12 h-12 rounded bg-gold-500/10 flex items-center justify-center text-gold-500 text-xl mb-6 group-hover:bg-gold-500 group-hover:text-navy-900 transition">
                        <i class="fa-solid fa-file-shield"></i>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-3">Taxation & Compliance</h4>
                    <p class="text-gray-400 text-sm leading-relaxed">Direct and indirect tax planning, filings, corporate filing support, and advisory services.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-24">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div>
                <h2 class="text-gold-500 font-semibold tracking-wide uppercase text-sm mb-2">Trusted Professionalism</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-white mb-6">Dedicated Counsel & Financial Integrity</h3>
                <p class="text-gray-400 leading-relaxed mb-6">
                    At <strong>A A Gaikwad & Associates</strong>, we pride ourselves on providing precise, timely, and confidential legal and financial guidance. Operating from Virar West, we cater to businesses and individuals seeking dependable, expert solutions under one roof.
                </p>
                <div class="flex items-center space-x-3 text-gray-300">
                    <i class="fa-solid fa-location-dot text-gold-500 text-xl"></i>
                    <span><strong>Office:</strong> Shop No 22, Sambhavnath Heights, Jain Mandir Rd, Virar West, 401303</span>
                </div>
            </div>
            <div class="bg-navy-800 p-8 rounded-xl border border-gray-700/50 shadow-2xl">
                <h4 class="text-xl font-bold text-white mb-4">Quick Contact Info</h4>
                <ul class="space-y-4 text-gray-300 text-sm">
                    <li class="flex items-center">
                        <i class="fa-solid fa-phone text-gold-500 mr-4 text-lg"></i>
                        <div>
                            <span class="block text-xs text-gray-400 uppercase tracking-wider">Phone Number</span>
                            <a href="tel:9850085712" class="font-semibold text-white hover:text-gold-500 text-base">9850085712</a>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <i class="fa-solid fa-map-location-dot text-gold-500 mr-4 text-lg mt-1"></i>
                        <div>
                            <span class="block text-xs text-gray-400 uppercase tracking-wider">Location</span>
                            <span class="text-gray-300">Shop No 22, Sambhavnath Heights, Jain Mandir Rd, Virar West, 401303</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 bg-navy-800/50 border-t border-gray-800">
        <div class="max-w-4xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-gold-500 font-semibold tracking-wide uppercase text-sm mb-2">Get in Touch</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-white">Book a Consultation</h3>
            </div>
            <form class="bg-navy-900 p-8 md:p-12 rounded-xl border border-gray-800 space-y-6">
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-xs font-semibold uppercase tracking-wider text-gray-400 mb-2">Full Name</label>
                        <input type="text" class="w-full bg-navy-800 border border-gray-700 rounded px-4 py-3 text-white focus:outline-none focus:border-gold-500 transition" placeholder="John Doe" required>
                    </div>
                    <div>
                        <label class="block text-xs font-semibold uppercase tracking-wider text-gray-400 mb-2">Phone Number</label>
                        <input type="tel" class="w-full bg-navy-800 border border-gray-700 rounded px-4 py-3 text-white focus:outline-none focus:border-gold-500 transition" placeholder="Your Phone Number" required>
                    </div>
                </div>
                <div>
                    <label class="block text-xs font-semibold uppercase tracking-wider text-gray-400 mb-2">Service Required</label>
                    <select class="w-full bg-navy-800 border border-gray-700 rounded px-4 py-3 text-white focus:outline-none focus:border-gold-500 transition">
                        <option>Legal & Advisory Services</option>
                        <option>Auditing & Assurance</option>
                        <option>Taxation & Compliance</option>
                        <option>General Consultation</option>
                    </select>
                </div>
                <div>
                    <label class="block text-xs font-semibold uppercase tracking-wider text-gray-400 mb-2">Message</label>
                    <textarea rows="4" class="w-full bg-navy-800 border border-gray-700 rounded px-4 py-3 text-white focus:outline-none focus:border-gold-500 transition" placeholder="Briefly describe your requirements..." required></textarea>
                </div>
                <button type="submit" class="w-full py-4 rounded bg-gold-500 text-navy-900 font-bold hover:bg-gold-600 transition shadow-lg">Submit Request</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-navy-900 border-t border-gray-800 py-12">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center text-sm text-gray-400 space-y-4 md:space-y-0">
            <div class="flex items-center space-x-3">
                <i class="fa-solid fa-scale-balanced text-gold-500 text-xl"></i>
                <span class="font-bold text-white tracking-wider">A A GAIKWAD & ASSOCIATES</span>
            </div>
            <p class="text-center md:text-right">Shop No 22, Sambhavnath Heights, Jain Mandir Rd, Virar West, 401303<br>&copy; 2026 All rights reserved.</p>
        </div>
    </footer>

    <!-- Simple Script for Mobile Menu Toggle -->
    <script>
        const btn = document.getElementById('menu-btn');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
