<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Image</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for the Inter font and overall background */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #1a202c; /* Dark background for a sleek look */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            color: #e2e8f0; /* Light text color */
        }
    </style>
</head>
<body>
    <div class="flex flex-col items-center justify-center p-6 sm:p-8 md:p-10 lg:p-12 bg-gray-800 rounded-2xl shadow-2xl max-w-sm sm:max-w-md md:max-w-lg lg:max-w-xl mx-4">
        <!-- Image Display -->
        <div class="relative w-full max-w-xs sm:max-w-sm md:max-w-md lg:max-w-lg overflow-hidden rounded-xl shadow-lg">
            <img
                src="http://googleusercontent.com/file_content/4"
                alt="Your Uploaded Image"
                class="w-full h-auto object-cover rounded-xl"
                onerror="this.onerror=null;this.src='https://placehold.co/600x600/3182ce/ffffff?text=Image+Not+Found';"
            >
        </div>
    </div>
</body>
</html>
