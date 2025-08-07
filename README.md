<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Credito Personale Rapido - Da Silva Alcide Mario Pinto</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        secondary: '#1f2937',
                        accent: '#10b981'
                    }
                }
            }
        }
    </script>
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #5D5CDE 0%, #3b82f6 100%);
        }
        .hero-pattern {
            background-image: url("data:image/svg+xml,%3csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3e%3cg fill='none' fill-rule='evenodd'%3e%3cg fill='%23ffffff' fill-opacity='0.1'%3e%3ccircle cx='30' cy='30' r='2'/%3e%3c/g%3e%3c/g%3e%3c/svg%3e");
        }
        .card-hover {
            transition: all 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
        .animate-float {
            animation: float 6s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
    </style>
</head>
<body class="bg-white dark:bg-gray-900 text-gray-900 dark:text-white transition-colors duration-300">

    <!-- Header -->
    <header class="bg-white/95 dark:bg-gray-900/95 backdrop-blur-sm border-b border-gray-200 dark:border-gray-700 sticky top-0 z-50">
        <nav class="container mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 bg-gradient-to-r from-primary to-blue-500 rounded-full flex items-center justify-center">
                        <i class="fas fa-euro-sign text-white text-lg"></i>
                    </div>
                    <div>
                        <h1 class="text-xl font-bold text-primary">Credito Personale Rapido</h1>
                        <p class="text-sm text-gray-600 dark:text-gray-400">Da Silva Alcide Mario Pinto</p>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-6">
                    <a href="#home" class="hover:text-primary transition-colors">Home</a>
                    <a href="#servizi" class="hover:text-primary transition-colors">Servizi</a>
                    <a href="#richiesta" class="hover:text-primary transition-colors">Richiesta</a>
                    <a href="#contatti" class="hover:text-primary transition-colors">Contatti</a>
                </div>
                <button id="mobileMenuBtn" class="md:hidden">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
            <!-- Mobile Menu -->
            <div id="mobileMenu" class="hidden mt-4 md:hidden">
                <div class="flex flex-col space-y-3 py-4 border-t border-gray-200 dark:border-gray-700">
                    <a href="#home" class="hover:text-primary transition-colors">Home</a>
                    <a href="#servizi" class="hover:text-primary transition-colors">Servizi</a>
                    <a href="#richiesta" class="hover:text-primary transition-colors">Richiesta</a>
                    <a href="#contatti" class="hover:text-primary transition-colors">Contatti</a>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg hero-pattern py-20 lg:py-32">
        <div class="container mx-auto px-4">
            <div class="max-w-4xl mx-auto text-center text-white">
                <div class="animate-float mb-8">
                    <div class="w-24 h-24 bg-white/20 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-handshake text-4xl"></i>
                    </div>
                </div>
                <h1 class="text-4xl lg:text-6xl font-bold mb-6 leading-tight">
                    Prestito Personale<br>
                    <span class="text-yellow-300">Rapido e Sicuro</span>
                </h1>
                <p class="text-xl lg:text-2xl mb-8 text-white/90">
                    Ottieni il tuo credito con un tasso fisso del <strong>2%</strong><br>
                    Approvazione rapida in 24 ore
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="#richiesta" class="bg-white text-primary font-semibold px-8 py-4 rounded-full hover:bg-gray-100 transition-all transform hover:scale-105 inline-flex items-center justify-center">
                        <i class="fas fa-credit-card mr-2"></i>
                        Richiedi Ora
                    </a>
                    <a href="https://wa.me/message/IBU2WZ7O6M72C1" target="_blank" class="border-2 border-white text-white font-semibold px-8 py-4 rounded-full hover:bg-white hover:text-primary transition-all transform hover:scale-105 inline-flex items-center justify-center">
                        <i class="fab fa-whatsapp mr-2"></i>
                        Contatta WhatsApp
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Caratteristiche -->
    <section class="py-20 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl lg:text-4xl font-bold mb-4">Perché Sceglierci?</h2>
                <p class="text-gray-600 dark:text-gray-400 text-lg max-w-2xl mx-auto">
                    Offriamo soluzioni di credito personalizzate con condizioni vantaggiose e processi semplificati
                </p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white dark:bg-gray-900 p-8 rounded-2xl shadow-lg card-hover">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-percentage text-primary text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Tasso Fisso 2%</h3>
                    <p class="text-gray-600 dark:text-gray-400">
                        Tasso di interesse fisso e competitivo del 2% per tutta la durata del prestito
                    </p>
                </div>
                <div class="bg-white dark:bg-gray-900 p-8 rounded-2xl shadow-lg card-hover">
                    <div class="w-16 h-16 bg-accent/10 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-clock text-accent text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Approvazione Rapida</h3>
                    <p class="text-gray-600 dark:text-gray-400">
                        Risposta in 24 ore e erogazione veloce del credito richiesto
                    </p>
                </div>
                <div class="bg-white dark:bg-gray-900 p-8 rounded-2xl shadow-lg card-hover">
                    <div class="w-16 h-16 bg-blue-500/10 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-shield-alt text-blue-500 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Sicurezza Garantita</h3>
                    <p class="text-gray-600 dark:text-gray-400">
                        Massima sicurezza nella gestione dei tuoi dati personali e finanziari
                    </p>
                </div>
                <div class="bg-white dark:bg-gray-900 p-8 rounded-2xl shadow-lg card-hover">
                    <div class="w-16 h-16 bg-green-500/10 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-euro-sign text-green-500 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Importi Flessibili</h3>
                    <p class="text-gray-600 dark:text-gray-400">
                        Da €1.000 a €50.000 con piani di rimborso personalizzabili
                    </p>
                </div>
                <div class="bg-white dark:bg-gray-900 p-8 rounded-2xl shadow-lg card-hover">
                    <div class="w-16 h-16 bg-purple-500/10 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-file-alt text-purple-500 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Poca Burocrazia</h3>
                    <p class="text-gray-600 dark:text-gray-400">
                        Procedure semplificate con documentazione minima richiesta
                    </p>
                </div>
                <div class="bg-white dark:bg-gray-900 p-8 rounded-2xl shadow-lg card-hover">
                    <div class="w-16 h-16 bg-red-500/10 rounded-full flex items-center justify-center mb-6">
                        <i class="fas fa-headset text-red-500 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Assistenza 24/7</h3>
                    <p class="text-gray-600 dark:text-gray-400">
                        Supporto continuo tramite WhatsApp ed email per ogni tua esigenza
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Servizi -->
    <section id="servizi" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl lg:text-4xl font-bold mb-4">I Nostri Servizi</h2>
                <p class="text-gray-600 dark:text-gray-400 text-lg max-w-2xl mx-auto">
                    Soluzioni di credito personalizzate per ogni tua necessità
                </p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gradient-to-br from-primary to-blue-500 p-8 rounded-2xl text-white card-hover">
                    <i class="fas fa-home text-4xl mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">Prestiti per Casa</h3>
                    <p class="text-white/90 mb-6">
                        Finanziamenti per acquisto, ristrutturazione o miglioramento della tua abitazione
                    </p>
                    <ul class="text-sm space-y-2 text-white/80">
                        <li>• Fino a €50.000</li>
                        <li>• Durata fino a 10 anni</li>
                        <li>• Tasso fisso 2%</li>
                    </ul>
                </div>
                <div class="bg-gradient-to-br from-accent to-green-600 p-8 rounded-2xl text-white card-hover">
                    <i class="fas fa-car text-4xl mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">Prestiti Auto</h3>
                    <p class="text-white/90 mb-6">
                        Finanziamenti per l'acquisto di auto nuove o usate con condizioni vantaggiose
                    </p>
                    <ul class="text-sm space-y-2 text-white/80">
                        <li>• Fino a €30.000</li>
                        <li>• Durata fino a 7 anni</li>
                        <li>• Approvazione veloce</li>
                    </ul>
                </div>
                <div class="bg-gradient-to-br from-orange-500 to-red-500 p-8 rounded-2xl text-white card-hover">
                    <i class="fas fa-graduation-cap text-4xl mb-6"></i>
                    <h3 class="text-xl font-bold mb-4">Prestiti Studio</h3>
                    <p class="text-white/90 mb-6">
                        Finanziamenti per percorsi formativi, università e corsi specializzanti
                    </p>
                    <ul class="text-sm space-y-2 text-white/80">
                        <li>• Fino a €20.000</li>
                        <li>• Durata fino a 5 anni</li>
                        <li>• Condizioni agevolate</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Modulo Richiesta -->
    <section id="richiesta" class="py-20 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <div class="max-w-4xl mx-auto">
                <div class="text-center mb-12">
                    <h2 class="text-3xl lg:text-4xl font-bold mb-4">Richiedi il Tuo Prestito</h2>
                    <p class="text-gray-600 dark:text-gray-400 text-lg">
                        Compila il modulo e riceverai una risposta entro 24 ore
                    </p>
                </div>
                <div class="bg-white dark:bg-gray-900 rounded-2xl shadow-xl p-8">
                    <form id="loanForm" class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-sm font-medium mb-2">Nome Completo *</label>
                                <input type="text" id="fullName" required class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Email *</label>
                                <input type="email" id="email" required class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white">
                            </div>
                        </div>
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-sm font-medium mb-2">Telefono *</label>
                                <input type="tel" id="phone" required class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Città *</label>
                                <input type="text" id="city" required class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white">
                            </div>
                        </div>
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-sm font-medium mb-2">Importo Richiesto *</label>
                                <select id="amount" required class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white">
                                    <option value="">Seleziona importo</option>
                                    <option value="1000-5000">€1.000 - €5.000</option>
                                    <option value="5000-10000">€5.000 - €10.000</option>
                                    <option value="10000-20000">€10.000 - €20.000</option>
                                    <option value="20000-30000">€20.000 - €30.000</option>
                                    <option value="30000-50000">€30.000 - €50.000</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Durata Prestito *</label>
                                <select id="duration" required class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white">
                                    <option value="">Seleziona durata</option>
                                    <option value="12">12 mesi</option>
                                    <option value="24">24 mesi</option>
                                    <option value="36">36 mesi</option>
                                    <option value="48">48 mesi</option>
                                    <option value="60">60 mesi</option>
                                    <option value="120">10 anni</option>
                                </select>
                            </div>
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-2">Finalità del Prestito *</label>
                            <select id="purpose" required class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white">
                                <option value="">Seleziona finalità</option>
                                <option value="casa">Casa/Ristrutturazione</option>
                                <option value="auto">Acquisto Auto</option>
                                <option value="studio">Studi/Formazione</option>
                                <option value="consolidamento">Consolidamento Debiti</option>
                                <option value="personale">Uso Personale</option>
                                <option value="altro">Altro</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-2">Note Aggiuntive</label>
                            <textarea id="notes" rows="4" class="w-full px-4 py-3 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent dark:bg-gray-800 dark:text-white" placeholder="Inserisci eventuali dettagli aggiuntivi..."></textarea>
                        </div>
                        <div class="flex items-start space-x-3">
                            <input type="checkbox" id="privacy" required class="mt-1 w-5 h-5 text-primary border-gray-300 rounded focus:ring-primary">
                            <label for="privacy" class="text-sm text-gray-600 dark:text-gray-400">
                                Accetto il trattamento dei dati personali secondo la normativa sulla privacy e autorizzo l'invio di comunicazioni commerciali *
                            </label>
                        </div>
                        <div class="flex flex-col sm:flex-row gap-4">
                            <button type="submit" class="flex-1 bg-primary text-white font-semibold px-8 py-4 rounded-lg hover:bg-primary/90 transition-all transform hover:scale-105 flex items-center justify-center">
                                <i class="fas fa-paper-plane mr-2"></i>
                                Invia Richiesta
                            </button>
                            <a href="https://wa.me/message/IBU2WZ7O6M72C1" target="_blank" class="flex-1 bg-green-500 text-white font-semibold px-8 py-4 rounded-lg hover:bg-green-600 transition-all transform hover:scale-105 flex items-center justify-center">
                                <i class="fab fa-whatsapp mr-2"></i>
                                WhatsApp Diretto
                            </a>
                            
