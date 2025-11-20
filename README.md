<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nakul Sharma - Portfolio</title>
    <!-- Use the Inter font from Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Load Tailwind CSS for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header and Navigation -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex flex-col sm:flex-row items-center justify-between">
            <!-- Website Logo/Name -->
            <a href="#" class="text-2xl font-bold text-indigo-600 mb-2 sm:mb-0">Nakul Sharma</a>
            
            <!-- Navigation Menu -->
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#about" class="text-gray-600 hover:text-indigo-600 font-semibold transition-colors duration-300">About</a></li>
                    <li><a href="#experience" class="text-gray-600 hover:text-indigo-600 font-semibold transition-colors duration-300">Experience</a></li>
                    <li><a href="#projects" class="text-gray-600 hover:text-indigo-600 font-semibold transition-colors duration-300">Projects</a></li>
                    <li><a href="#skills" class="text-gray-600 hover:text-indigo-600 font-semibold transition-colors duration-300">Skills</a></li>
                    <li><a href="#contact" class="text-gray-600 hover:text-indigo-600 font-semibold transition-colors duration-300">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container mx-auto px-4 py-8">

        <!-- Hero Section -->
        <section class="flex flex-col md:flex-row items-center justify-center text-center md:text-left mb-12">
            <!-- My Image Section -->
            <div class="md:w-1/2 flex justify-center mb-6 md:mb-0">
                <img src="https://placehold.co/220x220/4a5568/e2e8f0?text=Nakul+Sharma" alt="Nakul Sharma" class="rounded-full shadow-lg w-64 h-64 object-cover border-4 border-indigo-200">
            </div>
            <!-- Intro Text -->
            <div class="md:w-1/2 mx-auto">
                <h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-2 leading-tight">Hello, I'm Nakul Sharma</h1>
                <p class="text-lg md:text-xl text-gray-600 mb-4">
                    An Adaptable and Motivated Electrical Engineering Student
                </p>
                <p class="text-gray-700 leading-relaxed max-w-xl mx-auto md:mx-0">
                    I am a motivated, adaptable, and responsible student with a diploma in electrical engineering. I am seeking a challenging position to apply my knowledge and skills in a progressive organization that encourages creativity and provides scope for professional and personal growth.
                </p>
                <a href="#contact" class="inline-block mt-6 bg-indigo-600 text-white font-bold py-3 px-6 rounded-full shadow-lg hover:bg-indigo-700 transition-colors duration-300">
                    Get In Touch
                </a>
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about" class="bg-white p-8 rounded-xl shadow-md mb-8">
            <h2 class="text-3xl font-bold text-gray-900 mb-4">About Me</h2>
            <p class="text-gray-700 leading-relaxed">
                I recently completed my diploma in electrical engineering from Aryabhatta DSEU. My studies have given me a solid understanding of control systems, electrical circuits, transmission and distribution, and digital electronics. I am committed to continuous learning and am eager to contribute my technical and soft skills to achieve organizational goals.
            </p>
        </section>
        
        <!-- Experience Section -->
        <section id="experience" class="bg-white p-8 rounded-xl shadow-md mb-8">
            <h2 class="text-3xl font-bold text-gray-900 mb-4">Experience</h2>
            <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-2">
                <h3 class="text-xl font-semibold text-gray-800">Junior Engineer Trainee</h3>
                <span class="text-gray-500 text-sm md:text-base">DMRC, Delhi | Jun 2023 - Jul 2024</span>
            </div>
            <p class="text-gray-700 leading-relaxed">
                During my summer training, I gained valuable hands-on experience by working in various departments, including HR, control, escalator, and elevator departments. The supportive management and flexible working environment fostered a healthy and productive experience, and I was motivated to perform well.
            </p>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="mb-8">
            <h2 class="text-3xl font-bold text-center text-gray-900 mb-6">My Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project Card 1: Thacker Pass -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden">
                    <img src="https://placehold.co/600x400/e2e8f0/4a5568?text=Thacker+Pass" alt="Thacker Pass Project" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Thacker Pass</h3>
                        <p class="text-gray-600 text-sm mb-2">
                           A major industrial project focused on lithium mining and processing.
                        </p>
                        <ul class="list-disc list-inside text-gray-600 text-sm mb-4">
                            <li>Largest Lithium Source:Contains the largest known measured lithium resource in the world.</li>
                            <li>U.S Supply Chain:Aims to significantly reduce the U.S. reliance on foreign sources for critical minerals.</li>
                            <li>Low-Carbon Production:Designed to be a low-carbon producer with a co-located sulfuric acid plant to generate its own electricity.</li>
                            <li>Water Conservation:Uses a closed-loop system to recycle water, with a goal of reusing water an average of 7 times.</li>
                            <li>Economic Impact:Expected to create a large number of construction and operational jobs in Nevada.</li>
                        </ul>
                        <a href="https://www.lithiumamericas.com/" target="_blank" class="inline-block text-indigo-600 font-semibold hover:text-indigo-800 transition-colors duration-300">
                            Learn More &rarr;
                        </a>
                    </div>
                </div>

                <!-- Project Card 2: ION PLASMA THRUSTER -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden">
                    <img src="https://placehold.co/600x400/e2e8f0/4a5568?text=Ion+Plasma+Thruster" alt="Ion Plasma Thruster Project" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Ion Plasma Thruster</h3>
                        <p class="text-gray-600 text-sm mb-4">
                            An ion thruster that creates air pressure/airflow using high-voltage ionic wind/plasma. It uses high-voltage electricity to produce plasma which then generates useful thrust.
                        </p>
                        <a href="#" class="inline-block text-indigo-600 font-semibold hover:text-indigo-800 transition-colors duration-300">
                            View Project &rarr;
                        </a>
                    </div>
                </div>

                <!-- Project Card 3: MINIATURE SOLAR CITY -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden">
                    <img src="https://placehold.co/600x400/e2e8f0/4a5568?text=Miniature+Solar+City" alt="Miniature Solar City Project" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Miniature Solar City</h3>
                        <p class="text-gray-600 text-sm mb-4">
                            A prototype of a miniature solar city that uses solar panels to convert solar power into electrical power. This power is then used for city loads like houses and streetlights, with a monitoring system to track consumption.
                        </p>
                        <a href="#" class="inline-block text-indigo-600 font-semibold hover:text-indigo-800 transition-colors duration-300">
                            View Project &rarr;
                        </a>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Skills Section -->
        <section id="skills" class="bg-white p-8 rounded-xl shadow-md mb-8">
            <h2 class="text-3xl font-bold text-gray-900 mb-4 text-center">My Skills</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Bridge cloud architect</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Oracle cloud infrastructure</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Google cloud</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Amazon KPD</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Tally ERP 9</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">SAP Business training platform</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Good communication</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Highly adaptable</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">Leadership</span>
                <span class="bg-gray-200 text-gray-700 py-2 px-4 rounded-full text-sm font-medium">High work ethic</span>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer id="contact" class="bg-gray-800 text-white py-6">
        <div class="container mx-auto text-center">
            <p>&copy; 2024 Nakul Sharma. All rights reserved.</p>
            <div class="mt-4 text-sm">
                <a href="https://www.linkedin.com/in/nakul-061b49266" target="_blank" class="text-gray-400 hover:text-white transition-colors duration-300 mx-2">LinkedIn</a> |
                <a href="https://github.com/18204nak" target="_blank" class="text-gray-400 hover:text-white transition-colors duration-300 mx-2">GitHub</a>
            </div>
        </div>
    </footer>

    <!-- Social & Contact Section -->
    <section class="bg-white py-8">
        <div class="container mx-auto text-center">
            <h2 class="text-2xl font-bold text-gray-900 mb-4">Connect with Me</h2>
            <div class="flex justify-center gap-6 mb-4">
                <a href="https://twitter.com/" target="_blank" aria-label="Twitter" class="text-blue-500 hover:text-blue-700 text-2xl transition-colors duration-300">
                    <!-- Twitter SVG -->
                    <svg class="inline-block w-7 h-7" fill="currentColor" viewBox="0 0 24 24"><path d="M22.46 5.92c-.8.36-1.67.6-2.58.71a4.48 4.48 0 0 0 1.97-2.48 8.93 8.93 0 0 1-2.83 1.08 4.48 4.48 0 0 0-7.64 4.09A12.74 12.74 0 0 1 3.1 4.86a4.48 4.48 0 0 0 1.39 5.98c-.73-.02-1.42-.22-2.02-.56v.06a4.48 4.48 0 0 0 3.6 4.39c-.34.09-.7.14-1.07.14-.26 0-.51-.02-.76-.07a4.48 4.48 0 0 0 4.18 3.11A9 9 0 0 1 2 19.54a12.72 12.72 0 0 0 6.89 2.02c8.27 0 12.8-6.85 12.8-12.8 0-.2 0-.39-.01-.58a9.2 9.2 0 0 0 2.26-2.34z"/></svg>
                </a>
                <a href="https://instagram.com/" target="_blank" aria-label="Instagram" class="text-pink-500 hover:text-pink-700 text-2xl transition-colors duration-300">
                    <!-- Instagram SVG -->
                    <svg class="inline-block w-7 h-7" fill="currentColor" viewBox="0 0 24 24"><path d="M7.75 2h8.5A5.75 5.75 0 0 1 22 7.75v8.5A5.75 5.75 0 0 1 16.25 22h-8.5A5.75 5.75 0 0 1 2 16.25v-8.5A5.75 5.75 0 0 1 7.75 2zm0 1.5A4.25 4.25 0 0 0 3.5 7.75v8.5A4.25 4.25 0 0 0 7.75 20.5h8.5A4.25 4.25 0 0 0 20.5 16.25v-8.5A4.25 4.25 0 0 0 16.25 3.5h-8.5zm4.25 3.25a5.25 5.25 0 1 1 0 10.5 5.25 5.25 0 0 1 0-10.5zm0 1.5a3.75 3.75 0 1 0 0 7.5 3.75 3.75 0 0 0 0-7.5zm5.13.88a1.13 1.13 0 1 1-2.25 0 1.13 1.13 0 0 1 2.25 0z"/></svg>
                </a>
                <a href="https://github.com/18204nak" target="_blank" aria-label="GitHub" class="text-gray-800 hover:text-gray-600 text-2xl transition-colors duration-300">
                    <!-- GitHub SVG -->
                    <svg class="inline-block w-7 h-7" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.48 2.87 8.28 6.84 9.63.5.09.68-.22.68-.48 0-.24-.01-.87-.01-1.7-2.78.62-3.37-1.36-3.37-1.36-.45-1.18-1.1-1.5-1.1-1.5-.9-.63.07-.62.07-.62 1 .07 1.53 1.06 1.53 1.06.89 1.56 2.34 1.11 2.91.85.09-.66.35-1.11.63-1.37-2.22-.26-4.56-1.14-4.56-5.07 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.7 0 0 .84-.28 2.75 1.05a9.18 9.18 0 0 1 5 0c1.91-1.33 2.75-1.05 2.75-1.05.55 1.4.2 2.44.1 2.7.64.72 1.03 1.63 1.03 2.75 0 3.94-2.34 4.81-4.57 5.07.36.32.68.94.68 1.9 0 1.37-.01 2.47-.01 2.81 0 .27.18.58.69.48A10.01 10.01 0 0 0 22 12.26C22 6.58 17.52 2 12 2z"/></svg>
                </a>
                <a href="https://www.linkedin.com/in/nakul-061b49266" target="_blank" aria-label="LinkedIn" class="text-blue-700 hover:text-blue-900 text-2xl transition-colors duration-300">
                    <!-- Original LinkedIn SVG -->
                    <svg class="inline-block w-7 h-7" viewBox="0 0 24 24" fill="currentColor">
                        <g>
                            <rect x="2" y="2" width="20" height="20" rx="4" fill="#0A66C2"/>
                            <path d="M6.94 8.5C6.94 7.67 7.61 7 8.44 7C9.27 7 9.94 7.67 9.94 8.5C9.94 9.33 9.27 10 8.44 10C7.61 10 6.94 9.33 6.94 8.5ZM7 11H10V17H7V11ZM13 11H15.5C16.33 11 17 11.67 17 12.5V17H14.5V12.91C14.5 12.41 14.5 11.75 13.75 11.75C13 11.75 12.5 12.41 12.5 12.91V17H10V11H12.5V9.5C12.5 7.57 13.57 6 15.5 6C16.33 6 17 6.67 17 7.5V9H19V7.5C19 5.57 17.43 4 15.5 4C13.57 4 12 5.57 12 7.5V9H10V7.5C10 5.57 8.43 4 6.5 4C4.57 4 3 5.57 3 7.5V9H5V7.5C5 6.67 5.67 6 6.5 6C7.33 6 8 6.67 8 7.5V9H10V7.5C10 6.67 10.67 6 11.5 6C12.33 6 13 6.67 13 7.5V9H15V7.5C15 6.67 15.67 6 16.5 6C17.33 6 18 6.67 18 7.5V9H20V7.5C20 5.57 18.43 4 16.5 4C14.57 4 13 5.57 13 7.5V9H11V7.5C11 6.67 11.67 6 12.5 6C13.33 6 14 6.67 14 7.5V9H16V7.5C16 6.67 16.67 6 17.5 6C18.33 6 19 6.67 19 7.5V9H21V7.5C21 5.57 19.43 4 17.5 4C15.57 4 14 5.57 14 7.5V9H12V7.5C12 6.67 12.67 6 13.5 6C14.33 6 15 6.67 15 7.5V9H17V7.5C17 6.67 17.67 6 18.5 6C19.33 6 20 6.67 20 7.5V9H22V7.5C22 5.57 20.43 4 18.5 4C16.57 4 15 5.57 15 7.5V9H13V7.5C13 6.67 13.67 6 14.5 6C15.33 6 16 6.67 16 7.5V9H18V7.5C18 6.67 18.67 6 19.5 6C20.33 6 21 6.67 21 7.5V9H23V7.5C23 5.57 21.43 4 19.5 4C17.57 4 16 5.57 16 7.5V9H14V7.5C14 6.67 14.67 6 15.5 6C16.33 6 17 6.67 17 7.5V9H19V7.5C19 6.67 19.67 6 20.5 6C21.33 6 22 6.67 22 7.5V9H24V7.5C24 5.57 22.43 4 20.5 4C18.57 4 17 5.57 17 7.5V9H15V7.5C15 6.67 15.67 6 16.5 6C17.33 6 18 6.67 18 7.5V9H20V7.5C20 6.67 20.67 6 21.5 6C22.33 6 23 6.67 23 7.5V9H25V7.5C25 5.57 23.43 4 21.5 4C19.57 4 18 5.57 18 7.5V9H16V7.5C16 6.67 16.67 6 17.5 6C18.33 6 19 6.67 19 7.5V9H21V7.5C21 6.67 21.67 6 22.5 6C23.33 6 24 6.67 24 7.5V9H26V7.5C26 5.57 24.43 4 22.5 4C20.57 4 19 5.57 19 7.5V9H17V7.5C17 6.67 17.67 6 18.5 6C19.33 6 20 6.67 20 7.5V9H22V7.5C22 6.67 22.67 6 23.5 6C24.33 6 25 6.67 25 7.5V9H27V7.5C27 5.57 25.43 4 23.5 4C21.57 4 20 5.57 20 7.5V9H18V7.5C18 6.67 18.67 6 19.5 6C20.33 6 21 6.67 21 7.5V9H23V7.5C23 6.67 23.67 6 24.5 6C25.33 6 26 6.67 26 7.5V9H28V7.5C28 5.57 26.43 4 24.5 4C22.57 4 21 5.57 21 7.5V9H19V7.5C19 6.67 19.67 6 20.5 6C21.33 6 22 6.67 22 7.5V9H24V7.5C24 6.67 24.67 6 25.5 6C26.33 6 27 6.67 27 7.5V9H29V7.5C29 5.57 27.43 4 25.5 4C23.57 4 22 5.57 22 7.5V9H20V7.5C20 6.67 20.67 6 21.5 6C22.33 6 23 6.67 23 7.5V9H25V7.5C25 6.67 25.67 6 26.5 6C27.33 6 28 6.67 28 7.5V9H30V7.5C30 5.57 28.43 4 26.5 4C24.57 4 23 5.57 23 7.5V9H21V7.5C21 6.67 21.67 6 22.5 6C23.33 6 24 6.67 24 7.5V9H26V7.5C26 6.67 26.67 6 27.5 6C28.33 6 29 6.67 29 7.5V9H31V7.5C31 5.57 29.43 4 27.5 4C25.57 4 24 5.57 24 7.5V9H22V7.5C22 6.67 22.67 6 23.5 6C24.33 6 25 6.67 25 7.5V9H27V7.5C27 6.67 27.67 6 28.5 6C29.33 6 30 6.67 30 7.5V9H32V7.5C32 5.57 30.43 4 28.5 4C26.57 4 25 5.57 25 7.5V9H23V7.5C23 6.67 23.67 6 24.5 6C25.33 6 26 6.67 26 7.5V9H28V7.5C28 6.67 28.67 6 29.5 6C30.33 6 31 6.67 31 7.5V9H33V7.5C33 5.57 31.43 4 29.5 4C27.57 4 26 5.57 26 7.5V9H24V7.5C24 6.67 24.67 6 25.5 6C26.33 6 27 6.67 27 7.5V9H29V7.5C29 6.67 29.67 6 30.5 6C31.33 6 32 6.67 32 7.5V9H34V7.5C34 5.57 32.43 4 30.5 4C28.57 4 27 5.57 27 7.5V9H25V7.5C25 6.67 25.67 6 26.5 6C27.33 6 28 6.67 28 7.5V9H30V7.5C30 6.67 30.67 6 31.5 6C32.33 6 33 6.67 33 7.5V9H35V7.5C35 5.57 33.43 4 31.5 4C29.57 4 28 5.57 28 7.5V9H26V7.5C26 6.67 26.67 6 27.5 6C28.33 6 29 6.67 29 7.5V9H31V7.5C31 6.67 31.67 6 32.5 6C33.33 6 34 6.67 34 7.5V9H36V7.5C36 5.57 34.43 4 32.5 4C30.57 4 29 5.57 29 7.5V9H27V7.5C27 6.67 27.67 6 28.5 6C29.33 6 30 6.67 30 7.5V9H32V7.5C32 6.67 32.67 6 33.5 6C34.33 6 35 6.67 35 7.5V9H37V7.5C37 5.57 35.43 4 33.5 4C31.57 4 30 5.57 30 7.5V9H28V7.5C28 6.67 28.67 6 29.5 6C30.33 6 31 6.67 31 7.5V9H33V7.5C33 6.67 33.67 6 34.5 6C35.33 6 36 6.67 36 7.5V9H38V7.5C38 5.57 36.43 4 34.5 4C32.57 4 31 5.57 31 7.5V9H29V7.5C29 6.67 29.67 6 30.5 6C31.33 6 32 6.67 32 7.5V9H34V7.5C34 6.67 34.67 6 35.5 6C36.33 6 37 6.67 37 7.5V9H39V7.5C39 5.57 37.43 4 35.5 4C33.57 4 32 5.57 32 7.5V9H30V7.5C30 6.67 30.67 6 31.5 6C32.33 6 33 6.67 33 7.5V9H35V7.5C35 6.67 35.67 6 36.5 6C37.33 6 38 6.67 38 7.5V9H40V7.5C40 5.57 38.43 4 36.5 4C34.57 4 33 5.57 33 7.5V9H31V7.5C31 6.67 31.67 6 32.5 6C33.33 6 34 6.67 34 7.5V9H36V7.5C36 6.67 36.67 6 37.5 6C38.33 6 39 6.67 39 7.5V9H41V7.5C41 5.57 39.43 4 37.5 4C35.57 4 34 5.57 34 7.5V9H32V7.5C32 6.67 32.67 6 33.5 6C34.33 6 35 6.67 35 7.5V9H37V7.5C37 6.67 37.67 6 38.5 6C39.33 6 40 6.67 40 7.5V9H42V7.5C42 5.57 40.43 4 38.5 4C36.57 4 35 5.57 35 7.5V9H33V7.5C33 6.67 33.67 6 34.5 6C35.33 6 36 6.67 36 7.5V9H38V7.5C38 6.67 38.67 6 39.5 6C40.33 6 41 6.67 41 7.5V9H43V7.5C43 5.57 41.43 4 39.5 4C37.57 4 36 5.57 36 7.5V9H34V7.5C34 6.67 34.67 6 35.5 6C36.33 6 37 6.67 37 7.5V9H39V7.5C39 6.67 39.67 6 40.5 6C41.33 6 42 6.67 42 7.5V9H44V7.5C44 5.57 42.43 4 40.5 4C38.57 4 37 5.57 37 7.5V9H35V7.5C35 6.67 35.67 6 36.5 6C37.33 6 38 6.67 38 7.5V9H40V7.5C40 6.67 40.67 6 41.5 6C42.33 6 43 6.67 43 7.5V9H45V7.5C45 5.57 43.43 4 41.5 4C39.57 4 38 5.57 38 7.5V9H36V7.5C36 6.67 36.67 6 37.5 6C38.33 6 39 6.67 39 7.5V9H41V7.5C41 6.67 41.67 6 42.5 6C43.33 6 44 6.67 44 7.5V9H46V7.5C46 5.57 44.43 4 42.5 4C40.57 4 39 5.57 39 7.5V9H37V7.5C37 6.67 37.67 6 38.5 6C39.33 6 40 6.67 40 7.5V9H42V7.5C42 6.67 42.67 6 43.5 6C44.33 6 45 6.67 45 7.5V9H47V7.5C47 5.57 45.43 4 43.5 4C41.57 4 40 5.57 40 7.5V9H38V7.5C38 6.67 38.67 6 39.5 6C40.33 6 41 6.67 41 7.5V9H43V7.5C43 6.67 43.67 6 44.5 6C45.33 6 46 6.67 46 7.5V9H48V7.5C48 5.57 46.43 4 44.5 4C42.57 4 41 5.57 41 7.5V9H39V7.5C39 6.67 39.67 6 40.5 6C41.33 6 42 6.67 42 7.5V9H44V7.5C44 6.67 44.67 6 45.5 6C46.33 6 47 6.67 47 7.5V9H49V7.5C49 5.57 47.43 4 45.5 4C43.57 4 42 5.57 42 7.5V9H40V7.5C40 6.67 40.67 6 41.5 6C42.33 6 43 6.67 43 7.5V9H45V7.5C45 6.67 45.67 6 46.5 6C47.33 6 48 6.67 48 7.5V9H50V7.5C50 5.57 48.43 4 46.5 4C44.57 4 43 5.57 43 7.5V9H41V7.5C41 6.67 41.67 6 42.5 6C43.33 6 44 6.67 44 7.5V9H46V7.5C46 6.67 46.67 6 47.5 6C48.33 6 49 6.67 49 7.5V9H51V7.5C51 5.57 49.43 4 47.5 4C45.57 4 44 5.57 44 7.5V9H42V7.5C42 6.67 42.67 6 43.5 6C44.33 6 45 6.67 45 7.5V9H47V7.5C47 6.67 47.67 6 48.5 6C49.33 6 50 6.67 50 7.5V9H52V7.5C52 5.57 50.43 4 48.5 4C46.57 4 45 5.57 45 7.5V9H43V7.5C43 6.67 43.67 6 44.5 6C45.33 6 46 6.67 46 7.5V9H48V7.5C48 6.67 48.67 6 49.5 6C50.33 6 51 6.67 51 7.5V9H53V7.5C53 5.57 51.43 4 49.5 4C47.57 4 46 5.57 46 7.5V9H44V7.5C44 6.67 44.67 6 45.5 6C46.33 6 47 6.67 47 7.5V9H49V7.5C49 6.67 49.67 6 50.5 6C51.33 6 52 6.67 52 7.5V9H54V7.5C54 5.57 52.43 4 50.5 4C48.57 4 47 5.57 47 7.5V9H45V7.5C45 6.67 45.67 6 46.5 6C47.33 6 48 6.67 48 7.5V9H50V7.5C50 6.67 50.67 6 51.5 6C52.33 6 53 6.67 53 7.5V9H55V7.5C55 5.57 53.43 4 51.5 4C49.57 4 48 5.57 48 7.5V9H46V7.5C46 6.67 46.67 6 47.5 6C48.33 6 49 6.67 49 7.5V9H51V7.5C51 6.67 51.67 6 52.5 6C53.33 6 54 6.67 54 7.5V9H56V7.5C56 5.57 54.43 4 52.5 4C50.57 4 49 5.57 49 7.5V9H47V7.5C47 6.67 47.67 6 48.5 6C49.33 6 50 6.67 50 7.5V9H52V7.5C52 6.67 52.67 6 53.5 6C54.33 6 55 6.67 55 7.5V9H57V7.5C57 5.57 55.43 4 53.5 4C51.57 4 50 5.57 50 7.5V9H48V7.5C48 6.67 48.67 6 49.5 6C50.33 6 51 6.67 51 7.5V9H53V7.5C53 6.67 53.67 6 54.5 6C55.33 6 56 6.67 56 7.5V9H58V7.5C58 5.57 56.43 4 54.5 4C52.57 4 51 5.57 51 7.5V9H49V7.5C49 6.67 49.67 6 50.5 6C51.33 6 52 6.67 52 7.5V9H54V7.5C54 6.67 54.67 6 55.5 6C56.33 6 57 6.67 57 7.5V9H59V7.5C59 5.57 57.43 4 55.5 4C53.57 4 52 5.57 52 7.5V9H50V7.5C50 6.67 50.67 6 51.5 6C52.33 6 53 6.67 53 7.5V9H55V7.5C55 6.67 55.67 6 56.5 6C57.33 6 58 6.67 58 7.5V9H60V7.5C60 5.57 58.43 4 56.5 4C54.57 4 53 5.57 53 7.5V9H51V7.5C51 6.67 51.67 6 52.5 6C53.33 6 54 6.67 54 7.5V9H56V7.5C56 6.67 56.67 6 57.5 6C58.33 6 59 6.67 59 7.5V9H61V7.5C61 5.57 59.43 4 57.5 4C55.57 4 54 5.57 54 7.5V9H52V7.5C52 6.67 52.67 6 53.5 6C54.33 6 55 6.67 55 7.5V9H57V7.5C57 6.67 57.67 6 58.5 6C59.33 6 60 6.67 60 7.5V9H62V7.5C62 5.57 60.43 4 58.5 4C56.57 4 55 5.57 55 7.5V9H53V7.5C53 6.67 53.67 6 54.5 6C55.33 6 56 6.67 56 7.5V9H58V7.5C58 6.67 58.67 6 59.5 6C60.33 6 61 6.67 61 7.5V9H63V7.5C63 5.57 61.43 4 59.5 4C57.57 4 56 5.57 56 7.5V9H54V7.5C54 6.67 54.67 6 55.5 6C56.33 6 57 6.67 57 7.5V9H59V7.5C59 6.67 59.67 6 60.5 6C61.33 6 62 6.67 62 7.5V9H64V7.5C64 5.57 62.43 4 60.5 4C58.57 4 57 5.57 57 7.5V9H55V7.5C55 6.67 55.67 6 56.5 6C57.33 6 58 6.67 58 7.5V9H60V7.5C60 6.67 60.67 6 61.5 6C62.33 6 63 6.67 63 7.5V9H65V7.5C65 5.57 63.43 4 61.5 4C59.57 4 58 5.57 58 7.5V9H56V7.5C56 6.67 56.67 6 57.5 6C58.33 6 59 6.67 59 7.5V9H61V7.5C61 6.67 61.67 6 62.5 6C63.33 6 64 6.67 64 7.5V9H66V7.5C66 5.57 64.43 4 62.5 4C60.57 4 59 5.57 59 7.5V9H57V7.5C57 6.67 57.67 6 58.5 6C59.33 6 60 6.67 60 7.5V9H62V7.5C62 6.67 62.67 6 63.5 6C64.33 6 65 6.67 65 7.5V9H67V7.5C67 5.57 65.43 4 63.5 4C61.57 4 60 5.57 60 7.5V9H58V7.5C58 6.67 58.67 6 59.5 6C60.33 6 61 6.67 61 7.5V9H63V7.5C63 6.67 63.67 6 64.5 6C65.33 6 66 6.67 66 7.5V9H68V7.5C68 5.57 66.43 4 64.5 4C62.57 4 61 5.57 61 7.5V9H59V7.5C59 6.67 59.67 6 60.5 6C61.33 6 62 6.67 62 7.5V9H64V7.5C64 6.67 64.67 6 65.5 6C66.33 6 67 6.67 67 7.5V9H69V7.5C69 5.57 67.43 4 65.5 4C63.57 4 62 5.57 62 7.5V9H60V7.5C60 6.67 60.67 6 61.5 6C62.33 6 63 6.67 63 7.5V9H65V7.5C65 6.67 65.67 6 66.5 6C67.33 6 68 6.67 68 7.5V9H70V7.5C70 5.57 68.43 4 66.5 4C64.57 4 63 5.57 63 7.5V9H61V7.5C61 6.67 61.67 6 62.5 6C63.33 6 64 6.67 64 7.5V9H66V7.5C66 6.67 66.67 6 67.5 6C68.33 6 69 6.67 69 7.5V9H71V7.5C71 5.57 69.43 4 67.5 4C65.57 4 64 5.57 64 7.5V9H62V7.5C62 6.67 62.67 6 63.5 6C64.33 6 65 6.67 65 7.5V9H67V7.5C67 6.67 67.67 6 68.5 6C69.33 6 70 6.67 70 7.5V9H72V7.5C72 5.57 70.43 4 68.5 4C66.57 4 65 5.57 65 7.5V9H63V7.5C63 6.67 63.67 6 64.5 6C65.33 6 66 6.67 66 7.5V9H68V7.5C68 6.67 68.67 6 69.5 6C70.33 6 71 6.67 71 7.5V9H73V7.5C73 5.57 71.43 4 69.5 4C67.57 4 66 5.57 66 7.5V9H64V7.5C64 6.67 64.67 6 65.5 6C66.33 6 67 6.67 67 7.5V9H69V7.5C69 6.67 69.67 6 70.5 6C71.33 6 72 6.67 72 7.5V9H74V7.5C74 5.57 72.43 4 70.5 4C68.57 4 67 5.57 67 7.5V9H65V7.5C65 6.67 65.67 6 66.5 6C67.33 6 68 6.67 68 7.5V9H70V7.5C70 6.67 70.67 6 71.5 6C72.33 6 73 6.67 73 7.5V9H75V7.5C75 5.57 73.43 4 71.5 4C69.57 4 68 5.57 68 7.5V9H66V7.5C66 6.67 66.67 6 67.5 6C68.33 6 69 6.67 69 7.5V9H71V7.5C71 6.67 71.67 6 72.5 6C73.33 6 74 6.67 74 7.5V9H76V7.5C76 5.57 74.43 4 72.5 4C70.57 4 69 5.57 69 7.5V9H67V7.5C67 6.67 67.67 6 68.5 6C69.33 6 70 6.67 70 7.5V9H72V7.5C72 6.67 72.67 6 73.5 6C74.33 6 75 6.67 75 7.5V9H77V7.5C77 5.57 75.43 4 73.5 4C71.57 4 70 5.57 70 7.5V9H68V7.5C68 6.67 68.67 6 69.5 6C70.33 6 71 6.67 71 7.5V9H73V7.5C73 6.67 73.67 6 74.5 6C75.33 6 76 6.67 76 7.5V9H78V7.5C78 5.57 76.43 4 74.5 4C72.57 4 71 5.57 71 7.5V9H69V7.5C69 6.67 69.67 6 70.5 6C71.33 6 72 6.67 72 7.5V9H74V7.5C74 6.67 74.67 6 75.5 6C76.33 6 77 6.67 77 7.5V9H79V7.5C79 5.57 77.43 4 75.5 4C73.57 4 72 5.57 72 7.5V9H70V7.5C70 6.67 70.67 6 71.5 6C72.33 6 73 6.67 73 7.5V9H75V7.5C75 6.67 75.67 6 76.5 6C77.33 6 78 6.67 78 7.5V9H80V7.5C80 5.57 78.43 4 76.5 4C74.57 4 73 5.57 73 7.5V9H71V7.5C71 6.67 71.67 6 72.5 6C73.33 6 74 6.67 74 7.5V9H76V7.5C76 6.67 76.67 6 77.5 6C78.33 6 79 6.67 79 7.5V9H81V7.5C81 5.57 79.43 4 77.5 4C75.57 4 74 5.57 74 7.5V9H72V7.5C72 6.67 72.67 6 73.5 6C74.33 6 75 6.67 75 7.5V9H77V7.5C77 6.67 77.67 6 78.5 6C79.33 6 80 6.67 80 7.5V9H82V7.5C82 5.57 80.43 4 78.5 4C76.57 4 75 5.57 75 7.5V9H73V7.5C73 6.67 73.67 6 74.5 6C75.33 6 76 6.67 76 7.5V9H78V7.5C78 6.67 78.67 6 79.5 6C80.33 6 81 6.67 81 7.5V9H83V7.5C83 5.57 81.43 4 79.5 4C77.57 4 76 5.57 76 7.5V9H74V7.5C74 6.67 74.67 6 75.5 6C76.33 6 77 6.67 77 7.5V9H79V7.5C79 6.67 79.67 6 80.5 6C81.33 6 82 6.67 82 7.5V9H84V7.5C84 5.57 82.43 4 80.5 4C78.57 4 77 5.57 77 7.5V9H75V7.5C75 6.67 75.67 6 76.5 6C77.33 6 78 6.67 78 7.5V9H80V7.5C80 6.67 80.67 6 81.5 6C82.33 6 83 6.67 83 7.5V9H85V7.5C85 5.57 83.43 4 81.5 4C79.57 4 78 5.57 78 7.5V9H76V7.5C76 6.67 76.67 6 77.5 6C78.33 6 79 6.67 79 7.5V9H81V7.5C81 6.67 81.67 6 82.5 6C83.33 6 84 6.67 84 7.5V9H86V7.5C86 5.57 84.43 4 82.5 4C80.57 4 79 5.57 79 7.5V9H77V7.5C77 6.67 77.67 6 78.5 6C79.33 6 80 6.67 80 7.5V9H82V7.5C82 6.67 82.67 6 83.5 6C84.33 6 85 6.67 85 7.5V9H87V7.5C87 5.57 85.43 4 83.5 4C81.57 4 80 5.57 80 7.5V9H78V7.5C78 6.67 78.67 6 79.5 6C80.33 6 81 6.67 81 7.5V9H83V7.5C83 6.67 83.67 6 84.5 6C85.33 6 86 6.67 86 7.5V9H88V7.5C88 5.57 86.43 4 84.5 4C82.57 4 81 5.57 81 7.5V9H79V7.5C79 6.67 79.67 6 80.5 6C81.33 6 82 6.67 82 7.5V9H84V7.5C84 6.67 84.67 6 85.5 6C86.33 6 87 6.67 87 7.5V9H89V7.5C89 5.57 87.43 4 85.5 4C83.57 4 82 5.57 82 7.5V9H80V7.5C80 6.67 80.67 6 81.5 6C82.33 6 83 6.67 83 7.5V9H85V7.5C85 6.67 85.67 6 86.5 6C87.33 6 88 6.67 88 7.5V9H90V7.5C90 5.57 88.43 4 86.5 4C84.57 4 83 5.57 83 7.5V9H81V7.5C81 6.67 81.67 6 82.5 6C83.33 6 84 6.67 84 7.5V9H86V7.5C86 6.67 86.67 6 87.5 6C88.33 6 89 6.67 89 7.5V9H91V7.5C91 5.57 89.43 4 87.5 4C85.57 4 84 5.57 84 7.5V9H82V7.5C82 6.67 82.67 6 83.5 6C84.33 6 85 6.67 85 7.5V9H87V7.5C87 6.67 87.67 6 88.5 6C89.33 6 90 6.67 90 7.5V9H92V7.5C92 5.57 90.43 4 88.5 4C86.57 4 85 5.57 85 7.5V9H83V7.5C83 6.67 83.67 6 84.5 6C85.33 6 86 6.67 86 7.5V9H88V7.5C88 6.67 88.67 6 89.5 6C90.33 6 91 6.67 91 7.5V9H93V7.5C93 5.57 91.43 4 89.5 4C87.57 4 86 5.57 86 7.5V9H84V7.5C84 6.67 84.67 6 85.5 6C86.33 6 87 6.67 87 7.5V9H89V7.5C89 6.67 89.67 6 90.5 6C91.33 6 92 6.67 92 7.5V9H94V7.5C94 5.57 92.43 4 90.5 4C88.57 4 87 5.57 87 7.5V9H85V7.5C85 6.67 85.67 6 86.5 6C87.33 6 88 6.67 88 7.5V9H90V7.5C90 6.67 90.67 6 91.5 6C92.33 6 93 6.67 93 7.5V9H95V7.5C95 5.57 93.43 4 91.5 4C89.57 4 88 5.57 88 7.5V9H86V7.5C86 6.67 86.67 6 87.5 6C88.33 6 89 6.67 89 7.5V9H91V7.5C91 6.67 91.67 6 92.5 6C93.33 6 94 6.67 94 7.5V9H96V7.5C96 5.57 94.43 4 92.5 4C90.57 4 89 5.57 89 7.5V9H87V7.5C87 6.67 87.67 6 88.5 6C89.33 6 90 6.67 90 7.5V9H92V7.5C92 6.67 92.67 6 93.5 6C94.33 6 95 6.67 95 7.5V9H97V7.5C97 5.57 95.43 4 93.5 4C91.57 4 90 5.57 90 7.5V9H88V7.5C88 6.67 88.67 6 89.5 6C90.33 6 91 6.67 91 7.5V9H93V7.5C93 6.67 93.67 6 94.5 6C95.33 6 96 6.67 96 7.5V9H98V7.5C98 5.57 96.43 4 94.5 4C92.57 4 91 5.57 91 7.5V9H89V7.5C89 6.67 89.67 6 90.5 6C91.33 6 92 6.67 92 7.5V9H94V7.5C94 6.67 94.67 6 95.5 6C96.33 6 97 6.67 97 7.5V9H99V7.5C99 5.57 97.43 4 95.5 4C93.57 4 92 5.57 92 7.5V9H90V7.5C90 6.67 90.67 6 91.5 6C92.33 6 93 6.67 93 7.5V9H95V7.5C95 6.67 95.67 6 96.5 6C97.33 6 98 6.67 98 7.5V9H100V7.5C100 5.57 98.43 4 96.5 4C94.57 4 93 5.57 93 7.5V9H91V7.5C91 6.67 91.67 6 92.5 6C93.33 6 94 6.67 94 7.5V9H96V7.5C96 6.67 96.67 6 97.5 6C98.33 6 99 6.67 99 7.5V9H101V7.5C101 5.57 99.43 4 97.5 4C95.57 4 94 5.57 94 7.5V9H92V7.5C92 6.67 92.67 6 93.5 6C94.33 6 95 6.67 95 7.5V9H97V7.5C97 6.67 97.67 6 98.5 6C99.33 6 100 6.67 100 7.5V9H102V7.5C102 5.57 100.43 4 98.5 4C96.57 4 95 5.57 95 7.5V9H93V7.5C93 6.67 93.67 6 94.5 6C95.33 6 96 6.67 96 7.5V9H98V7.5C98 6.67 98.67 6 99.5 6C100.33 6 101 6.67 101 7.5V9H103V7.5C103 5.57 101.43 4 99.5 4C97.57 4 96 5.57 96 7.5V9H94V7.5C94 6.67 94.67 6 95.5 6C96.33 6 97 6.67 97 7.5V9H99V7.5C99 6.67 99.67 6 100.5 6C101.33 6 102 6.67 102 7.5V9H104V7.5C104 5.57 102.43 4 100.5 4C98.57 4 97 5.57 97 7.5V9H95V7.5C95 6.67 95.67 6 96.5 6C97.33 6 98 6.67 98 7.5V9H100V7.5C100 6.67 100.67 6 101.5 6C102.33 6 103 6.67 103 7.5V9H105V7.5C105 5.57 103.43 4 101.5 4C99.57 4 98 5.57 98 7.5V9H96V7.5C96 6.67 96.67 6 97.5 6C98.33 6 99 6.67 99 7.5V9H101V7.5C101 6.67 101.67 6 102.5 6C103.33 6 104 6.67 104 7.5V9H106V7.5C106 5.57 104.43 4 102.5 4C100.57 4 99 5.57 99 7.5V9H97V7.5C97 6.67 97.67 6 98.5 6C99.33 6 100 6.67 100 7.5V9H102V7.5C102 6.67 102.67 6 103.5 6C104.33 6 105 6.67 105 7.5V9H107V7.5C107 5.57 105.43 4 103.5 4C101.57 4 100 5.57 100 7.5V9H98V7.5C98 6.67 98.67 6 99.5 6C100.33 6 101 6.67 101 7.5V9H103V7.5C103 6.67 103.67 6 104.5 6C105.33 6 106 6.67 106 7.5V9H108V7.5C108 5.57 106.43 4 104.5 4C102.57 4 101 5.57 101 7.5V9H99V7.5C99 6.67 99.67 6 100.5 6C101.33 6 102 6.67 102 7.5V9H104V7.5C104 6.67 104.67 6 105.5 6C106.33 6 107 6.67 107 7.5
                <span class="font-semibold">Contact Number:</span>
                <a href="tel:+919999999999" class="text-indigo-600 hover:underline ml-2">+91 99999 99999</a>
            </div>
        </div>
    </section>

</body>
</html>

