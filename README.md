<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Didhiti Solutions | Interior, Automation & Security</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Premium Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brandDark: '#0B0F19',
                        brandGold: '#D4AF37',
                        brandAccent: '#1E293B'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-brandDark text-gray-100 font-sans antialiased">

    <!-- Header / Navigation -->
    <header class="fixed w-full top-0 z-50 bg-brandDark/80 backdrop-blur-md border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold tracking-wider text-white flex items-center gap-2">
                <span class="text-brandGold"><i class="fa-solid fa-layer-group"></i></span> DIDHITI <span class="text-sm font-light text-gray-400 tracking-normal">SOLUTIONS</span>
            </a>
            <nav class="hidden md:flex space-x-8 text-sm font-medium tracking-wide">
                <a href="#services" class="hover:text-brandGold transition-colors">Our Expertise</a>
                <a href="#about" class="hover:text-brandGold transition-colors">Why Choose Us</a>
                <a href="#contact" class="hover:text-brandGold transition-colors">Get a Quote</a>
            </nav>
            <a href="#contact" class="bg-brandGold text-brandDark font-semibold px-5 py-2 rounded-full text-sm hover:bg-white transition-all shadow-lg shadow-brandGold/20">
                Consult Now
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden">
        <!-- Background Overlay Image Grid / Minimal Abstract Representation -->
        <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_top_right,_var(--tw-gradient-stops))] from-brandGold/10 via-brandDark to-brandDark -z-10"></div>
        
        <div class="max-w-5xl mx-auto px-6 text-center">
            <span class="text-xs uppercase tracking-widest text-brandGold font-semibold bg-brandGold/10 px-4 py-1.5 rounded-full inline-block mb-6">
                The Future of Living Space
            </span>
            <h1 class="text-4xl md:text-6xl font-extrabold text-white tracking-tight mb-6 leading-tight">
                Luxury Interior Design Meets <br>
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-brandGold to-yellow-500">Smart Automation & Absolute Security</span>
            </h1>
            <p class="text-gray-400 text-lg md:text-xl max-w-3xl mx-auto mb-10 leading-relaxed">
                We craft breathtaking aesthetics, integrate cutting-edge smart home IoT architectures, and safeguard your sanctuary with premium military-grade surveillance.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#services" class="bg-white text-brandDark font-bold px-8 py-4 rounded-xl shadow-xl hover:bg-brandGold hover:text-brandDark transition-all">
                    Explore Solutions
                </a>
                <a href="#contact" class="border border-gray-700 bg-brandDark/50 backdrop-blur text-white font-semibold px-8 py-4 rounded-xl hover:bg-gray-800 transition-all">
                    Schedule Site Visit
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-24 bg-gray-950 border-t border-gray-900">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Our Tri-Core Ecosystem</h2>
                <p class="text-gray-400 max-w-2xl mx-auto">Seamless synchronization of elegant architecture, intelligent controls, and constant situational awareness.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Core 1: Interior Design -->
                <div class="bg-brandDark p-8 rounded-2xl border border-gray-800 hover:border-brandGold/40 transition-all group">
                    <div class="w-14 h-14 bg-brandGold/10 rounded-xl flex items-center justify-center text-brandGold text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-couch"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Premium Interior Design</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">
                        Bespoke spatial planning, custom furniture architecture, luxury finishes, and lighting designs tailored entirely to your sophisticated lifestyle.
                    </p>
                    <span class="text-xs text-brandGold font-semibold tracking-wider uppercase group-hover:underline">Bespoke Spaces &rarr;</span>
                </div>

                <!-- Core 2: Home Automation -->
                <div class="bg-brandDark p-8 rounded-2xl border border-gray-800 hover:border-brandGold/40 transition-all group">
                    <div class="w-14 h-14 bg-blue-500/10 rounded-xl flex items-center justify-center text-blue-400 text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-house-laptop"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Smart Home Automation</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">
                        Centralized dynamic control over climate, smart ambient lighting setups, automated drapes, and multi-room audio controlled via voice or smartphone.
                    </p>
                    <span class="text-xs text-blue-400 font-semibold tracking-wider uppercase group-hover:underline">Intelligent IoT &rarr;</span>
                </div>

                <!-- Core 3: Security Surveillance -->
                <div class="bg-brandDark p-8 rounded-2xl border border-gray-800 hover:border-brandGold/40 transition-all group">
                    <div class="w-14 h-14 bg-red-500/10 rounded-xl flex items-center justify-center text-red-400 text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Surveillance & Security</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">
                        AI-powered intruder detection matrices, 4K crystal-clear optical perimeter cameras, biometric facial access logs, and real-time remote breach warnings.
                    </p>
                    <span class="text-xs text-red-400 font-semibold tracking-wider uppercase group-hover:underline">Total Safety &rarr;</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Detailed Features / About -->
    <section id="about" class="py-24 bg-brandDark">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div>
                <span class="text-xs font-bold uppercase tracking-widest text-brandGold block mb-3">Sophisticated Craftsmanship</span>
                <h2 class="text-3xl md:text-4xl font-bold text-white mb-6">Why Choose Didhiti Solutions?</h2>
                <p class="text-gray-400 mb-6 leading-relaxed">
                    We bridge the gap between pure artistic beauty and high-end tech execution. Our project layouts seamlessly weave heavy automated electrical conduits behind pristine wall panelling, ensuring your smart components work brilliantly without ruining your premium visual styling.
                </p>
                <div class="space-y-4">
                    <div class="flex items-start gap-3">
                        <div class="text-brandGold mt-1"><i class="fa-solid fa-circle-check"></i></div>
                        <div><strong class="text-white">End-to-End Delivery:</strong> From conceptual blueprints to hardware wiring.</div>
                    </div>
                    <div class="flex items-start gap-3">
                        <div class="text-brandGold mt-1"><i class="fa-solid fa-circle-check"></i></div>
                        <div><strong class="text-white">Zero Compromise Security:</strong> Fully isolated local networks for encryption.</div>
                    </div>
                </div>
            </div>
            <div class="bg-gradient-to-br from-brandAccent to-gray-950 p-8 rounded-2xl border border-gray-800 flex flex-col justify-between relative overflow-hidden h-80">
                <div class="absolute top-0 right-0 p-8 opacity-10 text-9xl text-white"><i class="fa-solid fa-building-user"></i></div>
                <div>
                    <h4 class="text-brandGold text-sm font-semibold tracking-widest uppercase mb-2">Operational Philosophy</h4>
                    <p class="text-xl text-white font-medium">"An space isn't luxury unless it remembers to adjust itself to your mood and keep your family absolutely protected."</p>
                </div>
                <div class="text-sm text-gray-500">— Didhiti Project Standard</div>
            </div>
        </div>
    </section>

    <!-- Lead / Contact Form Section -->
    <section id="contact" class="py-24 bg-gray-950 border-t border-gray-900">
        <div class="max-w-3xl mx-auto px-6 bg-brandDark p-8 md:p-12 rounded-3xl border border-gray-800 shadow-2xl">
            <div class="text-center mb-8">
                <h2 class="text-2xl md:text-3xl font-bold text-white mb-2">Initiate Your Project Layout</h2>
                <p class="text-gray-400 text-sm">Fill out the brief context below, and our specialized deployment architect will contact you.</p>
            </div>
            
            <!-- Integration note: Formsubmit.co helps route this static form straight to your email for free -->
            <form action="https://formsubmit.co/your-email@gmail.com" method="POST" class="space-y-6">
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-xs uppercase tracking-wider text-gray-400 mb-2 font-semibold">Your Name</label>
                        <input type="text" name="name" required class="w-full bg-gray-950 border border-gray-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brandGold transition-colors">
                    </div>
                    <div>
                        <label class="block text-xs uppercase tracking-wider text-gray-400 mb-2 font-semibold">Contact Number</label>
                        <input type="tel" name="phone" required class="w-full bg-gray-950 border border-gray-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brandGold transition-colors">
                    </div>
                </div>
                <div>
                    <label class="block text-xs uppercase tracking-wider text-gray-400 mb-2 font-semibold">Primary Business Requirement</label>
                    <select name="requirement" class="w-full bg-gray-950 border border-gray-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brandGold transition-colors">
                        <option>Complete Design + Automation + Security Package</option>
                        <option>Bespoke Luxury Interior Design Only</option>
                        <option>Smart Home IoT Automation Setup Only</option>
                        <option>Advanced Surveillance & Access Matrix Only</option>
                    </select>
                </div>
                <div>
                    <label class="block text-xs uppercase tracking-wider text-gray-400 mb-2 font-semibold">Project Scope Notes</label>
                    <textarea name="message" rows="4" placeholder="Mention home/commercial sq. footage or automation ideas..." class="w-full bg-gray-950 border border-gray-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brandGold transition-colors"></textarea>
                </div>
                <button type="submit" class="w-full bg-brandGold text-brandDark font-bold py-4 rounded-xl shadow-lg shadow-brandGold/10 hover:bg-white transition-all uppercase tracking-wider text-sm">
                    Submit Request
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-brandDark text-center text-xs text-gray-600 border-t border-gray-950">
        <p>&copy; 2026 Didhiti Solutions. All Rights Reserved. Engineered for Absolute Elegance and Peace of Mind.</p>
    </footer>

</body>
</html>
