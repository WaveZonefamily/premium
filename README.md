<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unlock Gemini Power - Gemini Accounts for Sale</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .gradient-text {
            background-image: linear-gradient(to right, #6EE7B7, #3B82F6, #9333EA);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
        }
        .btn-primary {
            background: linear-gradient(to right, #3b82f6, #6366f1);
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
            box-shadow: 0 4px 6px rgba(59, 130, 246, 0.2), 0 10px 15px rgba(99, 102, 241, 0.2);
        }
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 8px rgba(59, 130, 246, 0.3), 0 12px 20px rgba(99, 102, 241, 0.3);
        }
        .card {
            background-color: #161b22;
            border: 1px solid #30363d;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }
        .modal-overlay {
            background-color: rgba(0, 0, 0, 0.7);
            backdrop-filter: blur(5px);
            z-index: 9999;
        }
        /* New blob animation for a more dynamic feel */
        @keyframes blob {
            0% { transform: translate(-50%, -50%) scale(1); }
            33% { transform: translate(-70%, -60%) scale(1.1); }
            66% { transform: translate(-30%, -40%) scale(0.9); }
            100% { transform: translate(-50%, -50%) scale(1); }
        }
        .animate-blob {
            animation: blob 7s infinite;
        }
        .animation-delay-2000 { animation-delay: 2s; }
        .animation-delay-4000 { animation-delay: 4s; }
    </style>
</head>
<body class="bg-[#0d1117] text-[#c9d1d9] flex flex-col min-h-screen">

    <!-- Modal for "Buy Now" -->
    <div id="buyModal" class="fixed inset-0 hidden items-center justify-center p-4 modal-overlay">
        <div class="bg-gray-800 rounded-xl p-8 max-w-lg w-full shadow-2xl border border-gray-700 transform scale-95 transition-transform ease-out duration-200">
            <h3 class="text-2xl font-bold text-white mb-4 text-center">Place Your Order</h3>
            <p id="statusMessage" class="text-center text-green-400 font-medium mb-4 hidden"></p>
            <form id="orderForm" class="space-y-6">
                <div>
                    <label for="name" class="block text-sm font-medium text-gray-300">Full Name</label>
                    <input type="text" id="name" name="name" required class="mt-1 block w-full px-4 py-2 bg-gray-700 border border-gray-600 rounded-lg text-white focus:ring-blue-500 focus:border-blue-500">
                </div>
                <div>
                    <label for="email" class="block text-sm font-medium text-gray-300">Email Address</label>
                    <input type="email" id="email" name="email" required class="mt-1 block w-full px-4 py-2 bg-gray-700 border border-gray-600 rounded-lg text-white focus:ring-blue-500 focus:border-blue-500">
                </div>
                <div class="bg-gray-700 p-4 rounded-lg border border-gray-600">
                    <h4 class="text-lg font-bold text-white mb-2">Step 1: Make a Bank Transfer</h4>
                    <p class="text-sm text-gray-400 mb-4">Transfer the amount of <span class="font-bold text-white">1300 LKR</span> to the following account details. Please ensure the transfer is successful before proceeding.</p>
                    <div class="bg-gray-800 p-4 rounded-lg">
                        <p class="text-sm text-gray-300">
                            <!-- **TO DO: REPLACE THESE WITH YOUR SPECIFIC ACCOUNT DETAILS** -->
                            <span class="font-semibold text-white">Bank:</span> Bank of Ceylon<br>
                            <span class="font-semibold text-white">Account Name:</span> Tharusha Piumal<br>
                            <span class="font-semibold text-white">Account Number:</span> 93175023<br>
                            <span class="font-semibold text-white">Branch:</span> Anamaduwa
                        </p>
                    </div>
                </div>
                <div class="bg-gray-700 p-4 rounded-lg border border-gray-600">
                    <h4 class="text-lg font-bold text-white mb-2">Step 2: Upload Your Slip</h4>
                    <p class="text-sm text-gray-400 mb-4">Upload a clear <span class="font-bold text-white">photo or PDF</span> of your bank transfer slip to our designated Google Drive folder and copy the shareable link below.</p>
                    <!-- **TO DO: REPLACE 'your-folder-id' WITH YOUR OWN GOOGLE DRIVE FOLDER ID** -->
                    <a href="https://drive.google.com/drive/folders/your-folder-id" target="_blank" class="w-full inline-flex justify-center items-center py-2 px-4 rounded-lg text-blue-400 bg-gray-800 hover:bg-gray-700 transition-colors">
                        <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15h2v2h-2v-2zm0-10h2v8h-2V7z"/>
                        </svg>
                        Open Google Drive Upload
                    </a>
                </div>
                <div>
                    <label for="slipLink" class="block text-sm font-medium text-gray-300">Google Drive Link to Slip</label>
                    <input type="url" id="slipLink" name="slipLink" required class="mt-1 block w-full px-4 py-2 bg-gray-700 border border-gray-600 rounded-lg text-white focus:ring-blue-500 focus:border-blue-500" placeholder="https://drive.google.com/...">
                </div>
                <button type="submit" class="btn-primary w-full text-white font-semibold py-3 px-4 rounded-lg transition-colors">
                    Submit Order
                </button>
                <p class="text-center text-gray-400 text-xs">
                    Upon submission, your order will be recorded. We will contact you at the provided email address after verification.
                </p>
            </form>
            <button onclick="closeModal()" class="w-full text-white font-semibold py-3 px-4 rounded-lg mt-4 bg-transparent border border-gray-600 hover:bg-gray-700 transition-colors">
                Cancel
            </button>
        </div>
    </div>

    <!-- Header -->
    <header class="py-4 px-6 md:px-12 flex items-center justify-between sticky top-0 bg-[#0d1117] bg-opacity-80 backdrop-blur-sm z-50">
        <a href="#hero" class="flex items-center space-x-2">
            <svg class="h-8 w-8 text-blue-500" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2.25 14.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zm4.5 0c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zm1.5-4.5c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5.67 1.5 1.5 1.5 1.5-.67 1.5-1.5zM12 6c-2.76 0-5 2.24-5 5h10c0-2.76-2.24-5-5-5z"/>
            </svg>
            <span class="text-xl font-bold text-white">Gemini</span>
        </a>
        <button onclick="showModal()" class="btn-primary text-white font-semibold py-2 px-6 rounded-full text-sm hover:scale-105">
            Buy Now
        </button>
    </header>

    <main class="flex-grow">
        <!-- Hero Section -->
        <section id="hero" class="relative overflow-hidden py-16 md:py-24 text-center">
            <div class="container mx-auto px-4 relative z-10">
                <h1 class="text-4xl md:text-6xl font-extrabold leading-tight tracking-tight mb-4 gradient-text animate-pulse">
                    Unlock the Power of Gemini.
                </h1>
                <p class="text-lg md:text-xl max-w-2xl mx-auto mb-8 text-gray-300">
                    Gain exclusive access to the most advanced AI models, faster performance, and dedicated support with a verified Gemini account.
                </p>
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                    <button onclick="showModal()" class="btn-primary text-white font-semibold py-3 px-8 rounded-full text-lg hover:scale-105">
                        Get Your Account Today
                    </button>
                    <a href="#features" class="text-white font-semibold py-3 px-8 rounded-full border border-gray-600 hover:bg-gray-800 transition-colors">
                        Learn More
                    </a>
                </div>
            </div>
            <!-- Background Blob -->
            <div class="absolute inset-0 z-0">
                <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-purple-500 rounded-full mix-blend-multiply filter blur-3xl opacity-20 animate-blob"></div>
                <div class="absolute absolute top-1/2 left-1/2 transform translate-x-1/4 -translate-y-1/2 w-96 h-96 bg-blue-500 rounded-full mix-blend-multiply filter blur-3xl opacity-20 animate-blob animation-delay-2000"></div>
                <div class="absolute top-1/2 left-1/2 transform translate-x-1/2 translate-y-1/4 w-96 h-96 bg-green-500 rounded-full mix-blend-multiply filter blur-3xl opacity-20 animate-blob animation-delay-4000"></div>
            </div>
        </section>

        <!-- Features Section -->
        <section id="features" class="py-16 md:py-24">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Why You Need a Gemini Account</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Feature Card 1 -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-blue-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zM12 6c-2.21 0-4 1.79-4 4v.5c0 .28.22.5.5.5h7c.28 0 .5-.22.5-.5V10c0-2.21-1.79-4-4-4zm-2 6.5c-1.66 0-3 1.34-3 3s1.34 3 3 3 3-1.34 3-3-1.34-3-3-3z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">Advanced AI Models</h3>
                        <p class="text-gray-400 text-sm">
                            Access exclusive models and features not available to the public. Stay ahead of the curve with cutting-edge AI capabilities.
                        </p>
                    </div>
                    <!-- Feature Card 2 -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-green-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm4-12c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zM8 12c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">Faster Performance</h3>
                        <p class="text-gray-400 text-sm">
                            Experience low-latency responses and higher processing speeds for all your queries and tasks.
                        </p>
                    </div>
                    <!-- Feature Card 3 -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-purple-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-12c0-.55.45-1 1-1s1 .45 1 1v6c0 .55-.45 1-1 1s-1-.45-1-1v-6zM11 17h2v2h-2v-2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">Dedicated Support</h3>
                        <p class="text-gray-400 text-sm">
                            Receive prioritized, one-on-one support for any questions or technical issues you may encounter.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- New Advantages Section -->
        <section id="advantages" class="py-16 md:py-24">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">More Exclusive Advantages</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Advantage Card 1: 1 Year Support -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-red-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M19 4h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V8h14v12zM9 10H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">1 Year Support</h3>
                        <p class="text-gray-400 text-sm">
                            Enjoy peace of mind with a full year of dedicated technical and account support.
                        </p>
                    </div>
                    <!-- Advantage Card 2: VEO 3 Video Generations -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-pink-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M20 5H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 12H4V7h16v10zM9 13l6-3.75-6-3.75v7.5z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">Veo 3 Video Generations</h3>
                        <p class="text-gray-400 text-sm">
                            Create stunning, high-quality videos with the advanced Veo 3 model for your projects.
                        </p>
                    </div>
                    <!-- Advantage Card 3: Latest Gemini Model -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-yellow-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 17.27L18.18 21l-1.64-7.03L22 9.24l-7.19-.61L12 2 9.19 8.63 2 9.24l5.46 4.73L5.82 21z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">Latest Gemini Model</h3>
                        <p class="text-gray-400 text-sm">
                            Always have access to the most recent and powerful Gemini models as soon as they are released.
                        </p>
                    </div>
                    <!-- Advantage Card 4: 1 Month Canva Free -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-teal-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M18.5 12c-1.49 0-2.85-.4-3.95-1.09l-3.23 3.23c.39.81.65 1.7.65 2.62 0 2.21-1.79 4-4 4s-4-1.79-4-4 1.79-4 4-4c.92 0 1.8.26 2.61.65l3.24-3.24C12.4 7.35 12 5.99 12 4.5 12 2.01 14.01 0 16.5 0S21 2.01 21 4.5c0 2.21-1.79 4-4 4s-4-1.79-4-4c0-.92-.26-1.8-.65-2.61l-3.24 3.24C7.35 12.4 5.99 12 4.5 12 2.01 12 0 14.01 0 16.5S2.01 21 4.5 21 9 19 9 16.5c0-.92.26-1.8.65-2.61l3.24 3.24C12.4 17.35 12 18.71 12 20.2c0 2.21 1.79 4 4 4s4-1.79 4-4-1.79-4-4-4c-.92 0-1.8-.26-2.61-.65l-3.24 3.24C10.74 20.16 10 21.05 10 22.5z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">1 Month Canva Free</h3>
                        <p class="text-gray-400 text-sm">
                            Kickstart your creative projects with a one-month free subscription to Canva.
                        </p>
                    </div>
                    <!-- Advantage Card 5: 2TB Google Drive -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-indigo-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M19.35 10.04C18.67 6.59 15.64 4 12 4c-2.82 0-5.22 1.6-6.48 4.04C2.17 8.52 0 11.23 0 14c0 3.31 2.69 6 6 6h13c2.76 0 5-2.24 5-5 0-2.64-2.05-4.78-4.65-4.96zM13 14h-2v-2h2v2zm0-4h-2V8h2v2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">2TB Google Drive</h3>
                        <p class="text-gray-400 text-sm">
                            Securely store all your files with a massive 2TB of cloud storage.
                        </p>
                    </div>
                    <!-- Advantage Card 6: YouTube Premium/Music -->
                    <div class="card p-6 md:p-8 rounded-xl flex flex-col items-center text-center">
                        <div class="mb-4">
                            <svg class="h-12 w-12 text-red-500" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M21.58 7.15c-.17-.6-.82-1.03-1.43-1.07-1.45-.16-7.2-.16-8.58 0-.61.04-1.26.47-1.43 1.07-.17.6-.17 1.83 0 2.43.17.6.82 1.03 1.43 1.07 1.38.16 7.13.16 8.58 0 .61-.04 1.26-.47 1.43-1.07.17-.6.17-1.83 0-2.43zM10 15V9l6 3-6 3z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-bold mb-2 text-white">Low-Priced YouTube Premium</h3>
                        <p class="text-gray-400 text-sm">
                            Enjoy ad-free videos and music with a special discount on YouTube Premium and YouTube Music.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Pricing Section -->
        <section id="pricing" class="py-16 md:py-24 text-center">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Pricing</h2>
                <p class="text-lg text-gray-400 mb-12">Simple, transparent, and affordable pricing.</p>
                <div class="flex justify-center items-center">
                    <div class="card p-8 md:p-12 rounded-2xl w-full max-w-sm">
                        <h3 class="text-xl font-semibold mb-2 text-white">Standard Account</h3>
                        <p class="text-lg text-gray-400 mb-4">One-time purchase</p>
                        <p class="text-5xl font-extrabold text-white">
                            1300 LKR
                        </p>
                        <p class="text-gray-500 mt-2 text-sm">approx. $4.30 USD</p>
                        <ul class="text-gray-300 text-left mt-8 space-y-3">
                            <li class="flex items-center">
                                <svg class="h-5 w-5 text-green-400 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/></svg>
                                Verified Account Access
                            </li>
                            <li class="flex items-center">
                                <svg class="h-5 w-5 text-green-400 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/></svg>
                                Advanced Model Access
                            </li>
                            <li class="flex items-center">
                                <svg class="h-5 w-5 text-green-400 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/></svg>
                                Priority Support
                            </li>
                            <li class="flex items-center">
                                <svg class="h-5 w-5 text-green-400 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/></svg>
                                No Subscription Fees
                            </li>
                        </ul>
                        <button onclick="showModal()" class="btn-primary w-full text-white font-semibold py-3 px-8 rounded-full mt-8 text-lg hover:scale-105">
                            Buy Now
                        </button>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="py-8 text-center border-t border-gray-700 mt-12">
        <p class="text-gray-500 text-sm">&copy; 2025 Gemini Accounts. All rights reserved.</p>
    </footer>

    <!-- Firebase SDKs -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getFirestore, collection, addDoc } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";
        import { getAuth, signInAnonymously } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { setLogLevel } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";

        // Set Firebase debug logs
        setLogLevel('Debug');

        const firebaseConfig = JSON.parse(typeof __firebase_config !== 'undefined' ? __firebase_config : '{}');
        const appId = typeof __app_id !== 'undefined' ? __app_id : 'default-app-id';
        const initialAuthToken = typeof __initial_auth_token !== 'undefined' ? __initial_auth_token : null;

        // Initialize Firebase
        const app = initializeApp(firebaseConfig);
        const db = getFirestore(app);
        const auth = getAuth(app);

        // Function to handle the form submission
        async function handleFormSubmit(event) {
            event.preventDefault();

            const form = event.target;
            const name = form.name.value;
            const email = form.email.value;
            const slipLink = form.slipLink.value;

            const statusMessage = document.getElementById('statusMessage');
            statusMessage.textContent = 'Submitting order...';
            statusMessage.classList.remove('hidden');
            statusMessage.classList.remove('text-green-400', 'text-red-400');

            try {
                // Sign in anonymously if not already authenticated
                if (!auth.currentUser) {
                    await signInAnonymously(auth);
                }
                const userId = auth.currentUser.uid;

                const orderData = {
                    name: name,
                    email: email,
                    slipLink: slipLink,
                    orderDate: new Date(),
                    status: 'Pending Verification'
                };

                // Add a new document to the "orders" collection under the user's ID
                const ordersCollectionRef = collection(db, `artifacts/${appId}/users/${userId}/orders`);
                await addDoc(ordersCollectionRef, orderData);

                // Show success message
                statusMessage.textContent = 'Order submitted successfully! We will contact you soon.';
                statusMessage.classList.add('text-green-400');
                form.reset(); // Reset form fields
                setTimeout(() => closeModal(), 3000); // Close modal after 3 seconds
            } catch (e) {
                console.error("Error adding document: ", e);
                statusMessage.textContent = 'Failed to submit order. Please try again.';
                statusMessage.classList.add('text-red-400');
            }
        }

        document.getElementById('orderForm').addEventListener('submit', handleFormSubmit);

        // Basic modal functions
        window.showModal = function() {
            const modal = document.getElementById('buyModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            setTimeout(() => {
                modal.querySelector('.transform').classList.remove('scale-95');
                modal.querySelector('.transform').classList.add('scale-100');
            }, 10);
        }

        window.closeModal = function() {
            const modal = document.getElementById('buyModal');
            modal.querySelector('.transform').classList.remove('scale-100');
            modal.querySelector('.transform').classList.add('scale-95');
            setTimeout(() => {
                modal.classList.remove('flex');
                modal.classList.add('hidden');
            }, 200);
        }
    </script>
</body>
</html>
