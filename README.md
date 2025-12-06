<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Freshco – Fresh Grocery E-Commerce Website</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.3.3/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <div class="max-w-5xl mx-auto p-6">

        <!-- Header -->
        <header class="mb-8">
            <h1 class="text-4xl font-bold mb-2">🛒 Freshco – Fresh Grocery E-Commerce Website</h1>
            <p class="text-gray-600">Freshco is a modern and responsive <strong>fresh grocery shopping website</strong> built using <strong>React and Tailwind CSS</strong>. The website provides a smooth shopping experience with a clean UI, fast performance, product categories, brand showcases, and sliders.</p>
        </header>

        <!-- Table of Contents -->
        <section class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">📑 Table of Contents</h2>
            <ol class="list-decimal list-inside space-y-1 text-blue-600">
                <li><a href="#screenshot">Screenshot</a></li>
                <li><a href="#live-demo">Live Demo</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#tech-stack">Tech Stack</a></li>
                <li><a href="#dependencies">Dependencies & Purpose</a></li>
                <li><a href="#installation">Installation & Setup</a></li>
                <li><a href="#folder-structure">Folder Structure</a></li>
                <li><a href="#deployment">Deployment</a></li>
                <li><a href="#author">Author</a></li>
            </ol>
        </section>

        <!-- Screenshot -->
        <section id="screenshot" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">📸 Website Screenshot</h2>
            <p class="text-gray-600 mb-2">Add your screenshot in the project root as <code>screenshot.png</code></p>
            <img src="./screenshot.png" alt="Freshco Screenshot" class="rounded shadow-md w-full">
        </section>

        <!-- Live Demo -->
        <section id="live-demo" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">🔗 Live Demo</h2>
            <p class="text-blue-600 hover:underline"><a href="https://your-live-demo-link.com">https://your-live-demo-link.com</a></p>
        </section>

        <!-- Features -->
        <section id="features" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">✨ Features</h2>
            <ul class="list-disc list-inside space-y-1">
                <li>Fully responsive clean UI</li>
                <li>Category-based grocery browsing</li>
                <li>Add to cart & wishlist styled buttons</li>
                <li>Smooth scrolling brand strip</li>
                <li>Product slider / carousel</li>
                <li>Attractive discount banner</li>
                <li>Customer reviews section</li>
                <li>Fast loading & optimized assets</li>
            </ul>
        </section>

        <!-- Tech Stack -->
        <section id="tech-stack" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">🛠 Tech Stack</h2>
            <table class="table-auto border-collapse border border-gray-300 w-full">
                <thead>
                    <tr class="bg-gray-200">
                        <th class="border border-gray-300 px-4 py-2 text-left">Technology</th>
                        <th class="border border-gray-300 px-4 py-2 text-left">Purpose</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">React JS</td>
                        <td class="border border-gray-300 px-4 py-2">Frontend UI</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">Tailwind CSS</td>
                        <td class="border border-gray-300 px-4 py-2">Styling</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">React Router DOM</td>
                        <td class="border border-gray-300 px-4 py-2">Navigation / Multiple pages</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">Lucide React</td>
                        <td class="border border-gray-300 px-4 py-2">Premium icons</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">React Fast Marquee</td>
                        <td class="border border-gray-300 px-4 py-2">Auto-scrolling label strip</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">React Multi Carousel</td>
                        <td class="border border-gray-300 px-4 py-2">Product sliders</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Dependencies -->
        <section id="dependencies" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">📦 Dependencies & Purpose</h2>
            <table class="table-auto border-collapse border border-gray-300 w-full">
                <thead>
                    <tr class="bg-gray-200">
                        <th class="border border-gray-300 px-4 py-2 text-left">Package</th>
                        <th class="border border-gray-300 px-4 py-2 text-left">Work / Purpose</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">react</td>
                        <td class="border border-gray-300 px-4 py-2">Builds the UI using components</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">react-dom</td>
                        <td class="border border-gray-300 px-4 py-2">Renders React UI inside the browser</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">react-router-dom</td>
                        <td class="border border-gray-300 px-4 py-2">Handles routing & navigation</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">tailwindcss</td>
                        <td class="border border-gray-300 px-4 py-2">Fast modern styling using utility classes</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">@tailwindcss/vite</td>
                        <td class="border border-gray-300 px-4 py-2">Enables Tailwind + Vite integration</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">react-icons</td>
                        <td class="border border-gray-300 px-4 py-2">Provides multiple icon collections</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">lucide-react</td>
                        <td class="border border-gray-300 px-4 py-2">Lightweight premium icons</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">react-fast-marquee</td>
                        <td class="border border-gray-300 px-4 py-2">Auto-moving scrolling text & brand strip</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">react-multi-carousel</td>
                        <td class="border border-gray-300 px-4 py-2">Product slider / carousel component</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Installation -->
        <section id="installation" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">⚙️ Installation & Setup</h2>
            <pre class="bg-gray-100 p-4 rounded mb-2"><code># Clone the repository
git clone https://github.com/your-username/freshco.git

# Navigate into project
cd freshco

# Install dependencies
npm install

# Start development server
npm run dev
</code></pre>
        </section>

        <!-- Folder Structure -->
        <section id="folder-structure" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">📁 Folder Structure</h2>
            <pre class="bg-gray-100 p-4 rounded"><code>freshco/
 ┣ public/
 ┣ src/
 ┃ ┣ assets/
 ┃ ┣ components/
 ┃ ┣ pages/
 ┃ ┣ App.jsx
 ┃ ┗ main.jsx
 ┣ package.json
 ┣ tailwind.config.js
 ┗ README.md
</code></pre>
        </section>

        <!-- Deployment -->
        <section id="deployment" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">🚀 Deployment</h2>
            <p>You can deploy this project on:</p>
            <table class="table-auto border-collapse border border-gray-300 w-full mt-2">
                <thead>
                    <tr class="bg-gray-200">
                        <th class="border border-gray-300 px-4 py-2">Platform</th>
                        <th class="border border-gray-300 px-4 py-2">Recommended</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">Vercel</td>
                        <td class="border border-gray-300 px-4 py-2">⭐ Best for React apps</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">Netlify</td>
                        <td class="border border-gray-300 px-4 py-2">⭐ Fast & free</td>
                    </tr>
                    <tr>
                        <td class="border border-gray-300 px-4 py-2">GitHub Pages</td>
                        <td class="border border-gray-300 px-4 py-2">⚠ Requires SPA routing config</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Author -->
        <section id="author" class="mb-8">
            <h2 class="text-2xl font-semibold mb-2">👨‍💻 Author</h2>
            <p><strong>Your Name</strong></p>
            <ul class="list-disc list-inside space-y-1 text-blue-600">
                <li>GitHub — <a href="https://github.com/your-username">https://github.com/your-username</a></li>
                <li>Email — <a href="mailto:your-email@example.com">your-email@example.com</a></li>
                <li>LinkedIn — <a href="#">Add your LinkedIn link</a></li>
                <li>Portfolio — <a href="#">Add your portfolio link</a></li>
            </ul>
        </section>

    </div>

</body>
</html>
