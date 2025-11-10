<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Wassam Rehman Khalid - CSE Portfolio</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Inter font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #6366f1; /* Indigo 500 */
        }
        body {
            font-family: 'Inter', sans-serif;
            transition: background-color 0.3s, color 0.3s;
        }
        /* Custom card style for minimal design */
        .project-card {
            border-left: 4px solid var(--primary-color);
            transition: all 0.3s;
        }
        .project-card:hover {
            box-shadow: 0 10px 15px -3px rgba(99, 102, 241, 0.2), 0 4px 6px -2px rgba(99, 102, 241, 0.1);
            transform: translateY(-2px);
        }
        .text-accent {
            color: var(--primary-color);
        }
    </style>
</head>
<body class="bg-gray-50 dark:bg-gray-900 text-gray-900 dark:text-gray-100 p-4 sm:p-8">

  <div class="max-w-5xl mx-auto">
        <!-- HEADER & PROFESSIONAL SUMMARY -->
        <header class="text-center mb-12 py-8 bg-white dark:bg-gray-800 rounded-xl shadow-lg">
            <h1 class="text-4xl sm:text-5xl font-extrabold text-accent mb-2">
                [Your Name]
            </h1>
            <p class="text-xl sm:text-2xl font-medium text-gray-600 dark:text-gray-300">
                Full Stack Developer | AI Automation Engineer
            </p>
            <p class="text-lg font-light text-gray-500 dark:text-gray-400 mt-1">
                Computer System Engineering B.S.
            </p>
        </header>
    <!-- CORE EXPERTISE -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold mb-4 border-b-2 border-accent pb-2">💡 Core Expertise & Mission</h2>
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
                <p class="text-lg leading-relaxed">
                    Highly analytical <span class="font-semibold text-accent">Computer System Engineer</span> specializing in the convergence of high-performance web architecture (<span class="font-mono">React, Tailwind</span>) and <span class="font-semibold text-accent">AI/Multimodal data solutions</span> (Gemini API, Flutter, Firebase). My work focuses on building robust, scalable systems for real-time analysis, consistently driving **measurable business impact**—including <span class="font-bold text-green-500">95% efficiency gains</span> and <span class="font-bold text-green-500">double-digit conversion improvements</span>.
                </p>
            </div>
        </section>
    <!-- FEATURED PROJECTS -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold mb-6 border-b-2 border-accent pb-2">💻 Featured Projects</h2>
            <div class="grid md:grid-cols-2 gap-8">
              <!-- Project 1: AI-Driven Infrastructure PCI Analyzer -->
                <div class="project-card bg-white dark:bg-gray-800 p-6 rounded-lg shadow-xl">
                    <h3 class="text-2xl font-semibold mb-3 text-accent">
                        AI-Driven Infrastructure PCI Analyzer 🤖
                    </h3>
                    <p class="mb-3">
                        <span class="font-medium">Focus:</span> Automated infrastructure health assessment combining real-time mobile **accelerometer** data (for **IRI**) and **Gemini API** computer vision for defect classification.
                    </p>
                    <ul class="list-none space-y-2 text-sm text-gray-700 dark:text-gray-300">
                        <li class="flex items-start">
                            <span class="text-lg text-green-500 mr-2">•</span>
                            <span class="font-bold">Tech:</span> **Flutter, Firebase Firestore**, Sensor Integration.
                        </li>
                        <li class="flex items-start">
                            <span class="text-lg text-green-500 mr-2">•</span>
                            <span class="font-bold">Impact:</span> Reduced manual analysis time from **7 days to 4 hours** (95% efficiency) and achieved a **22% improvement** in predictive maintenance scheduling accuracy.
                        </li>
                    </ul>
                    <a href="[GitHub Repository Link]" class="inline-block mt-4 text-accent hover:underline font-medium">View Repository &rarr;</a>
                </div>
              <!-- Project 2: E-commerce Conversion & Performance Portal -->
                <div class="project-card bg-white dark:bg-gray-800 p-6 rounded-lg shadow-xl">
                    <h3 class="text-2xl font-semibold mb-3 text-accent">
                        E-commerce Conversion & Performance Portal 🛒
                    </h3>
                    <p class="mb-3">
                        <span class="font-medium">Focus:</span> Full-stack redesign of an e-commerce checkout experience optimized for speed and conversion rate (CRO).
                    </p>
                    <ul class="list-none space-y-2 text-sm text-gray-700 dark:text-gray-300">
                        <li class="flex items-start">
                            <span class="text-lg text-green-500 mr-2">•</span>
                            <span class="font-bold">Tech:</span> **React, Tailwind CSS, Redux, D3.js**.
                        </li>
                        <li class="flex items-start">
                            <span class="text-lg text-green-500 mr-2">•</span>
                            <span class="font-bold">Impact:</span> Delivered a **7% increase in overall purchase conversion** and a **14% decrease in cart abandonment**. Achieved an average Google Lighthouse score of **94/100**.
                        </li>
                    </ul>
                    <a href="[GitHub Repository Link]" class="inline-block mt-4 text-accent hover:underline font-medium">View Repository &rarr;</a>
                </div>
            </div>
        </section>
<!-- TECHNICAL SKILLS -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold mb-6 border-b-2 border-accent pb-2">🛠️ Technical Skill Set</h2>
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
                
  <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-4">
                    <!-- Category 1 -->
                    <div class="p-4 bg-gray-100 dark:bg-gray-700 rounded-lg">
                        <h4 class="font-bold text-accent mb-2">Front-End / UX</h4>
                        <p class="text-sm">React, Tailwind CSS, Redux, D3.js (Visualization), WCAG 2.1</p>
                    </div>
                    <!-- Category 2 -->
                    <div class="p-4 bg-gray-100 dark:bg-gray-700 rounded-lg">
                        <h4 class="font-bold text-accent mb-2">Mobile / Data</h4>
                        <p class="text-sm">Flutter, Firebase (Firestore, Auth), Sensor Integration, IRI Calculation</p>
                    </div>
                    <!-- Category 3 -->
                    <div class="p-4 bg-gray-100 dark:bg-gray-700 rounded-lg">
                        <h4 class="font-bold text-accent mb-2">AI / Backend</h4>
                        <p class="text-sm">Gemini API (Multimodal), Serverless Architecture, RESTful API, GeoJSON</p>
                    </div>
                    <!-- Category 4 -->
                    <div class="p-4 bg-gray-100 dark:bg-gray-700 rounded-lg">
                        <h4 class="font-bold text-accent mb-2">Tools / Dev Ops</h4>
                        <p class="text-sm">Git/GitHub, VS Code, Google Lighthouse, Hotjar, Performance Optimization</p>
                    </div>
                </div>

  </div>
        </section>
<!-- CONTACT INFO -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold mb-6 border-b-2 border-accent pb-2">📧 Get In Touch</h2>
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md text-lg grid sm:grid-cols-3 gap-4">
                <div class="font-medium">
                    <span class="text-accent mr-2">Email:</span>
                    <a href="mailto:[Your Email Address]" class="hover:underline">wassamrehman@gmail.com</a>
                </div>
                <div class="font-medium">
                    <span class="text-accent mr-2">Mobile:</span>
                    <a href="tel:[Your Mobile Number]" class="hover:underline">+92-3137615415</a>
                </div>
                <div class="font-medium">
                    <span class="text-accent mr-2">Portfolio:</span>
                    <a href="[Your Portfolio/Public Website URL]" class="hover:underline">linkedin.com/wassamrehmankhalid</a>
                </div>
            </div>
        </section>
<!-- FOOTER -->
        <footer class="text-center text-sm text-gray-500 dark:text-gray-400 pt-8 mt-8 border-t border-gray-300 dark:border-gray-700">
            Thank you for visiting! Feel free to explore my repositories.
        </footer>
    </div>

</body>
</html>
