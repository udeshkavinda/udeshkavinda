<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kavinda Udesh GitHub Banner</title>
    <!-- Tailwind CSS CDN for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter for a modern look -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Ensure it takes full viewport height for centering */
            background-color: #0d1117; /* Dark background to see the banner clearly */
            font-family: 'Inter', sans-serif; /* Apply Inter globally */
        }
        .banner-container {
            width: 100%;
            max-width: 900px; /* Max width for larger screens */
            padding: 1.5rem; /* Responsive padding */
            box-sizing: border-box; /* Include padding in width */
        }
        /* Custom styles for the shiny gold effect */
        .text-shiny-gold {
            background: linear-gradient(to right, #FFD700, #DAA520, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shine 3s infinite;
            text-shadow: 0 0 8px rgba(255, 215, 0, 0.6);
        }

        @keyframes shine {
            0% { background-position: -200% center; }
            100% { background-position: 200% center; }
        }
    </style>
</head>
<body class="bg-gray-950"> <!-- Darker body background to make banner stand out -->
    <div class="banner-container">
        <!-- Main Banner Card -->
        <div class="bg-gradient-to-br from-gray-900 to-black rounded-3xl shadow-2xl overflow-hidden p-6 sm:p-8 md:p-10 lg:p-12 flex flex-col md:flex-row items-center justify-between text-white space-y-6 md:space-y-0 md:space-x-8">
            <!-- Left Section: Text Content -->
            <div class="flex flex-col items-center md:items-start text-center md:text-left flex-grow">
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold mb-3 leading-tight tracking-tight">
                    Hello, I'm <span class="text-shiny-gold drop-shadow-lg">Kavinda Udesh</span>!
                </h1>
                <p class="text-lg sm:text-xl lg:text-2xl font-light mb-4 opacity-95">
                    An Aspiring <span class="font-semibold">AI Specialist</span> & First-Year IT Undergraduate.
                </p>
                <p class="text-md sm:text-lg opacity-85">
                    Passionate about crafting intelligent solutions and innovating with code. 🚀
                </p>
                <div class="mt-6 flex flex-wrap justify-center md:justify-start gap-3">
                    <span class="inline-flex items-center px-3 py-1.5 rounded-full text-sm font-medium bg-yellow-400 bg-opacity-20 text-yellow-100 shadow-sm">
                        <svg class="w-4 h-4 mr-1.5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
                        Python
                    </span>
                    <span class="inline-flex items-center px-3 py-1.5 rounded-full text-sm font-medium bg-yellow-400 bg-opacity-20 text-yellow-100 shadow-sm">
                        <svg class="w-4 h-4 mr-1.5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9.25 17m4.5 0L14.25 17m7.5-6L12 10.5h-1.5a2.25 2.25 0 00-2.25 2.25v2.25a2.25 2.25 0 002.25 2.25h1.5l1.5-1.5h1.5m4.5-5.5a2.25 2.25 0 100 4.5 2.25 2.25 0 000-4.5z"></path></svg>
                        AI / ML
                    </span>
                    <span class="inline-flex items-center px-3 py-1.5 rounded-full text-sm font-medium bg-yellow-400 bg-opacity-20 text-yellow-100 shadow-sm">
                        <svg class="w-4 h-4 mr-1.5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 9l3 3-3 3m5 0h3M5 20h14a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                        Git
                    </span>
                </div>
            </div>

            <!-- Right Section: Profile Picture -->
            <div class="flex-shrink-0">
                <!-- IMPORTANT: Replace this placeholder image with your actual profile picture URL -->
                <!-- For the screenshot, you can either put your real URL here or keep the placeholder for now -->
                <img src="https://placehold.co/180x180/ADD8E6/000000?text=Kavinda" alt="Kavinda Udesh Profile Picture" class="w-36 h-36 sm:w-44 sm:h-44 lg:w-48 lg:h-48 rounded-full border-4 border-white shadow-xl object-cover">
            </div>
        </div>
    </div>
</body>
</html>




