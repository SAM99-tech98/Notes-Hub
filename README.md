<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Notes Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 dark:bg-gray-900 text-gray-800 dark:text-gray-200 min-h-screen p-6 transition-colors duration-200">
    <div class="max-w-4xl mx-auto bg-white dark:bg-gray-800 rounded-lg shadow-lg p-8">
        <div class="flex items-center mb-8">
            <i class="fas fa-book-open text-3xl text-indigo-600 mr-3"></i>
            <h1 class="text-3xl font-bold text-indigo-600">Notes Hub</h1>
        </div>
        
        <h2 class="text-2xl font-semibold mb-4 border-b pb-2 dark:border-gray-700">College Resource Sharing Platform</h2>
        
        <div class="mb-8">
            <h3 class="text-xl font-medium mb-3 text-indigo-500">📌 Description</h3>
            <p class="mb-4">Notes Hub is a comprehensive platform designed for students to access and share educational resources including lecture notes, study materials, and other academic content.</p>
            <p>The platform features a clean, responsive interface with dark mode support and integrates with Google Drive for file storage and management.</p>
        </div>
        
        <div class="mb-8">
            <h3 class="text-xl font-medium mb-3 text-indigo-500">✨ Features</h3>
            <ul class="space-y-2">
                <li class="flex items-start">
                    <i class="fas fa-folder text-indigo-400 mr-2 mt-1"></i>
                    <span>Organized folder structure for easy navigation</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-search text-indigo-400 mr-2 mt-1"></i>
                    <span>Powerful search functionality to find resources quickly</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-eye text-indigo-400 mr-2 mt-1"></i>
                    <span>File preview capability for supported formats</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-moon text-indigo-400 mr-2 mt-1"></i>
                    <span>Dark/light mode toggle</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-mobile-alt text-indigo-400 mr-2 mt-1"></i>
                    <span>Fully responsive design for all devices</span>
                </li>
                <li class="flex items-start">
                    <i class="fas fa-cloud-download-alt text-indigo-400 mr-2 mt-1"></i>
                    <span>Direct download links for all files</span>
                </li>
            </ul>
        </div>
        
        <div class="mb-8">
            <h3 class="text-xl font-medium mb-3 text-indigo-500">🛠️ Technologies Used</h3>
            <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
                <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg flex items-center">
                    <i class="fab fa-html5 text-orange-500 text-2xl mr-3"></i>
                    <span>HTML5</span>
                </div>
                <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg flex items-center">
                    <i class="fab fa-css3-alt text-blue-500 text-2xl mr-3"></i>
                    <span>CSS3</span>
                </div>
                <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg flex items-center">
                    <i class="fab fa-js-square text-yellow-400 text-2xl mr-3"></i>
                    <span>JavaScript</span>
                </div>
                <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg flex items-center">
                    <span class="text-indigo-500 font-bold text-xl mr-3">TW</span>
                    <span>Tailwind CSS</span>
                </div>
                <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg flex items-center">
                    <i class="fab fa-google-drive text-green-500 text-2xl mr-3"></i>
                    <span>Google Drive API</span>
                </div>
                <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg flex items-center">
                    <i class="fas fa-icons text-purple-500 text-2xl mr-3"></i>
                    <span>Font Awesome</span>
                </div>
            </div>
        </div>
        
        <div class="mb-8">
            <h3 class="text-xl font-medium mb-3 text-indigo-500">🚀 Getting Started</h3>
            <p class="mb-4">To use Notes Hub, simply open the HTML file in any modern web browser. No additional installation is required.</p>
            
            <div class="bg-gray-100 dark:bg-gray-700 p-4 rounded-lg mb-4">
                <h4 class="font-medium mb-2">For Development:</h4>
                <ol class="list-decimal pl-5 space-y-1">
                    <li>Clone or download the project files</li>
                    <li>Open <code class="bg-gray-200 dark:bg-gray-600 px-1 rounded">index.html</code> in your browser</li>
                    <li>For modifications, edit the HTML, CSS (Tailwind), or JavaScript as needed</li>
                </ol>
            </div>
        </div>
        
        <div class="mb-8">
            <h3 class="text-xl font-medium mb-3 text-indigo-500">📝 Notes</h3>
            <div class="bg-yellow-50 dark:bg-yellow-900 dark:bg-opacity-20 border-l-4 border-yellow-400 p-4">
                <p>The project currently uses a demo Google Drive API key. For production use, you should:</p>
                <ul class="list-disc pl-5 mt-2 space-y-1">
                    <li>Replace the API key with your own</li>
                    <li>Update the root folder ID to point to your Drive folder</li>
                    <li>Ensure your Drive folder has appropriate sharing settings</li>
                </ul>
            </div>
        </div>
        
        <div class="border-t dark:border-gray-700 pt-6">
            <p class="text-center text-gray-500 dark:text-gray-400">© 2023 Notes Hub Project</p>
        </div>
    </div>
    
    <script>
        tailwind.config = {
            darkMode: 'class',
        }
        
        // Set dark mode by default
        document.documentElement.classList.add('dark');
        localStorage.setItem('color-theme', 'dark');
    </script>
</body>
</html>
