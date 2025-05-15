<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Finzzep</title>
  

</head>
<body>
<!-- partial:index.partial.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inspired by Finzep</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .service-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-10px) scale(1.03);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.3);
            background-color: #111827;
        }
        .section {
            border-radius: 16px;
            padding: 7rem 0;
            background-size: cover;
            background-position: center;
        }
        header nav ul li a {
            font-size: 1.4rem;
            transition: color 0.3s ease;
        }
        header nav ul li a:hover {
            color: #ffffff;
        }
        .hero-content {
            animation: fadeIn 1s ease, slideIn 0.5s ease;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(50px); }
            to { transform: translateY(0); }
        }
        .product-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-10px) scale(1.03);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.3);
            background-color: #111827;
        }
        .fade-in {
            animation: fadeIn 1s ease;
        }
        .slide-in-left {
            animation: slideInLeft 0.5s ease;
        }
        @keyframes slideInLeft {
            from { transform: translateX(-50px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        @keyframes starColorChange {
            0% { background-color: #e0f7fa; /* Lightest */ }
            16.66% { background-color: #b2ebf2; }
            33.32% { background-color: #80deea; }
            49.98% { background-color: #4dd0e1; /* Medium */ }
            66.64% { background-color: #26c6da; }
            83.30% { background-color: #00bcd4; }
            100% { background-color: #e0f7fa; /* Lightest */ }
        }
        .star-animation {
            animation: starColorChange 10s infinite;
        }

        .service-details {
            display: none;
            padding-top: 1rem;
            color: #b8b8b8;
            font-size: 0.9rem;
        }
        .service-card.expanded .service-details {
            display: block;
        }

        .product-details {
            display: none;
            padding-top: 1rem;
            color: #b8b8b8;
            font-size: 0.9rem;
        }
        .product-card.expanded .product-details {
            display: block;
        }

        .logo-animation {
            animation: fadeIn 1s ease, slideIn 0.5s ease, pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }

    </style>
</head>
<body class="bg-gray-100">
    <header class="bg-black text-white py-8 flex justify-between items-center shadow-lg sticky top-0 z-10 rounded-md border-b-2 border-gray-800">
        <div class="logo text-4xl font-bold ml-8 text-white text-shadow-md logo-animation">Finzep</div>
        <nav class="mr-8">
            <ul class="flex space-x-8">
                <li><a href="#services" class="hover:text-gray-300 no-underline transition duration-300">Services</a></li>
                <li><a href="#products" class="hover:text-gray-300 no-underline transition duration-300">Products</a></li>
                <li><a href="#about" class="hover:text-gray-300 no-underline transition duration-300">About</a></li>
                <li><a href="#contact" class="hover:text-gray-300 no-underline transition duration-300">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero bg-gradient-to-br from-blue-500 to-purple-500 text-white text-center py-24 px-6 rounded-md shadow-lg star-animation" style="background-image: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'); background-blend-mode: multiply; background-size: cover; background-position: center;">
        <div class="hero-content" style="background-color: rgba(0, 0, 0, 0.6); padding: 4rem 0; border-radius: 12px;">
            <h1 class="text-6xl font-bold mb-10 text-white text-shadow-lg">Welcome</h1>
            <p class="text-3xl mb-16 text-white text-shadow-md">Your Innovation Partner</p>
            <button onclick="window.location.href='#contact'" class="bg-yellow-500 text-blue-900 py-4 px-10 rounded-full hover:bg-yellow-600 focus:outline-none focus:ring-4 focus:ring-yellow-300 focus:ring-opacity-75 text-xl transition duration-300 font-semibold shadow-md">Get Started</button>
        </div>
    </section>

    <section id="services" class="section bg-gray-100 py-16 px-4 text-center rounded-md star-animation" style="background-image: url('https://images.unsplash.com/photo-1556761175-b413da4baf72?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'); background-blend-mode: multiply; background-size: cover; background-position: center;">
        <div style="background-color: rgba(255, 255, 255, 0.8); padding: 4rem 0; border-radius: 12px;">
            <h2 class="text-4xl font-bold mb-12 text-blue-700 fade-in">Our Services</h2>
            <p class="text-xl text-gray-700 mb-10 max-w-4xl mx-auto fade-in">Driving your business forward with our expert services.</p>
            <div class="service-grid grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12 max-w-7xl mx-auto">
                <div class="service-card bg-gray-900 rounded-lg shadow-md p-8 flex flex-col justify-between slide-in-left text-white">
                    <h3 class="text-2xl font-semibold mb-6 text-green-400">Web Development</h3>
                    <p class="text-gray-300 mb-6 text-lg">Responsive websites that captivate.</p>
                    <ul class="list-disc list-inside text-gray-400 text-md">
                        <li onclick="toggleServiceDetails(this)">Responsive Design</li>
                        <div class="service-details">Ensures your site works on all devices, providing optimal viewing experience across desktops, tablets, and smartphones.</div>
                        <li onclick="toggleServiceDetails(this)">E-commerce</li>
                        <div class="service-details">We build online stores with secure payment gateways, shopping carts, and product management features to help you sell online effectively.</div>
                        <li onclick="toggleServiceDetails(this)">CMS</li>
                        <div class="service-details">Content Management Systems that allow you to easily update and manage your website content without needing technical skills.</div>
                    </ul>
                    <button onclick="showServiceDetails('web')" class="bg-gradient-to-r from-green-400 to-blue-500 text-white py-3 px-6 rounded-full hover:from-green-500 hover:to-blue-600 focus:outline-none focus:ring-4 focus:ring-green-300 focus:ring-opacity-75 text-lg transition duration-300 mt-6 font-semibold">Learn More</button>
                </div>
                <div class="service-card bg-gray-900 rounded-lg shadow-md p-8 flex flex-col justify-between slide-in-left text-white">
                    <h3 class="text-2xl font-semibold mb-6 text-purple-400">Mobile App Development</h3>
                    <p class="text-gray-300 mb-6 text-lg">Cross-platform mobile solutions.</p>
                     <ul class="list-disc list-inside text-gray-400 text-md">
                        <li onclick="toggleServiceDetails(this)">iOS</li>
                        <div class="service-details">Development of mobile applications for Apple devices, including iPhones and iPads, using Swift or Objective-C.</div>
                        <li onclick="toggleServiceDetails(this)">Android</li>
                        <div class="service-details">Building mobile applications for Android devices using Java or Kotlin, ensuring compatibility across various Android versions.</div>
                        <li onclick="toggleServiceDetails(this)">UI/UX</li>
                        <div class="service-details">Designing intuitive and user-friendly interfaces for mobile apps, focusing on enhancing user experience and engagement.</div>
                    </ul>
                    <button onclick="showServiceDetails('mobile')" class="bg-gradient-to-r from-purple-400 to-pink-500 text-white py-3 px-6 rounded-full hover:from-purple-500 hover:to-pink-600 focus:outline-none focus:ring-4 focus:ring-purple-300 focus:ring-opacity-75 text-lg transition duration-300 mt-6 font-semibold">Learn More</button>
                </div>
                <div class="service-card bg-gray-900 rounded-lg shadow-md p-8 flex flex-col justify-between slide-in-left text-white">
                    <h3 class="text-2xl font-semibold mb-6 text-yellow-400">Digital Marketing</h3>
                    <p class="text-gray-300 mb-6 text-lg">Effective online marketing strategies.</p>
                    <ul class="list-disc list-inside text-gray-400 text-md">
                        <li onclick="toggleServiceDetails(this)">SEO</li>
                        <div class="service-details">Search Engine Optimization to improve your website's visibility in search engine results and drive organic traffic.</div>
                        <li onclick="toggleServiceDetails(this)">Social Media</li>
                        <div class="service-details">Strategies to help you engage with your audience on social media platforms, build brand awareness, and drive sales.</div>
                        <li onclick="toggleServiceDetails(this)">PPC</li>
                        <div class="service-details">Pay-Per-Click advertising campaigns to help you get immediate traffic to your website through paid ads on search engines and other platforms.</div>
                    </ul>
                    <button onclick="showServiceDetails('digital')" class="bg-gradient-to-r from-yellow-400 to-orange-500 text-gray-900 py-3 px-6 rounded-full hover:from-yellow-500 hover:to-orange-600 focus:outline-none focus:ring-4 focus:ring-yellow-300 focus:ring-opacity-75 text-lg transition duration-300 mt-6 font-semibold">Learn More</button>
                </div>
            </div>
        </div>
    </section>

    <section id="products" class="section bg-blue-100 py-16 px-4 text-center rounded-md star-animation" style="background-image: url('https://images.unsplash.com/photo-1580489944061-499256545994?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'); background-blend-mode: multiply; background-size: cover; background-position: center;">
        <div style="background-color: rgba(255, 255, 255, 0.7); padding: 4rem 0; border-radius: 12px;">
            <h2 class="text-4xl font-bold mb-12 text-blue-700 fade-in">Our Products</h2>
             <p class="text-xl text-gray-700 mb-10 max-w-4xl mx-auto fade-in">Explore our innovative products.</p>
            <div class="product-grid grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12 max-w-7xl mx-auto">
                <div class="product-card bg-gray-900 rounded-lg shadow-md p-8 flex flex-col justify-between slide-in-left text-white">
                    <h3 class="text-2xl font-semibold mb-6 text-indigo-400">Streamline</h3>
                    <p class="text-gray-300 mb-6 text-lg">Workflow automation tool.</p>
                    <ul class="list-disc list-inside text-gray-400 text-md">
                        <li>Workflow Automation</li>
                        <li>Task Management</li>
                        <li>Reporting</li>
                    </ul>
                    <button class="bg-indigo-500 text-white py-3 px-6 rounded-full hover:bg-indigo-600 focus:outline-none focus:ring-4 focus:ring-indigo-300 focus:ring-opacity-75 text-lg transition duration-300 mt-6 font-semibold" onclick="showProductDetails('streamline')">View Details</button>
                    <div class="product-details text-gray-300">
                        <p>Streamline automates your repetitive tasks, helping you to focus on what matters most.  It integrates with your existing tools and provides powerful reporting.</p>
                    </div>
                </div>
                <div class="product-card bg-gray-900 rounded-lg shadow-md p-8 flex flex-col justify-between slide-in-left text-white">
                    <h3 class="text-2xl font-semibold mb-6 text-pink-400">Connect</h3>
                    <p class="text-gray-300 mb-6 text-lg">Communication platform.</p>
                     <ul class="list-disc list-inside text-gray-400 text-md">
                        <li>Team Chat</li>
                        <li>Video Conference</li>
                        <li>File Sharing</li>
                    </ul>
                    <button class="bg-pink-500 text-white py-3 px-6 rounded-full hover:bg-pink-600 focus:outline-none focus:ring-4 focus:ring-pink-300 focus:ring-opacity-75 text-lg transition duration-300 mt-6 font-semibold" onclick="showProductDetails('connect')">View Details</button>
                    <div class="product-details text-gray-300">
                         <p>Connect keeps your team connected with seamless communication.  Features include chat, video conferencing, and secure file sharing.</p>
                    </div>
                </div>
                <div class="product-card bg-gray-900 rounded-lg shadow-md p-8 flex flex-col justify-between slide-in-left text-white">
                    <h3 class="text-2xl font-semibold mb-6 text-teal-400">Insight</h3>
                    <p class="text-gray-300 mb-6 text-lg">Data analytics tool.</p>
                    <ul class="list-disc list-inside text-gray-400 text-md">
                        <li>Data Visualization</li>
                        <li>Predictive Analytics</li>
                        <li>Dashboards</li>
                    </ul>
                    <button class="bg-teal-500 text-white py-3 px-6 rounded-full hover:bg-teal-600 focus:outline-none focus:ring-4 focus:ring-teal-300 focus:ring-opacity-75 text-lg transition duration-300 mt-6 font-semibold" onclick="showProductDetails('insight')">View Details</button>
                    <div class="product-details text-gray-300">
                        <p>Insight provides you with the data you need to make informed decisions.  It offers powerful visualization and predictive analytics.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="section py-16 px-4 text-center rounded-md star-animation" style="background-image: url('https://images.unsplash.com/photo-1543965175-4726bc59cd04?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'); background-blend-mode: multiply; background-size: cover; background-position: center;">
        <div style="background-color: rgba(0, 0, 139, 0.8); padding: 4rem 0; border-radius: 12px;">
            <h2 class="text-4xl font-bold mb-12 text-white fade-in">About Us</h2>
            <p class="text-xl text-gray-300 mb-10 max-w-5xl mx-auto fade-in">
                We are a leading tech company dedicated to innovation and client success.  Our team of experts is passionate about developing cutting-edge solutions that drive growth and transform businesses.  With a client-centric approach, we strive to exceed expectations and build long-lasting partnerships. We believe in the power of technology to create a better future.
            </p>
        </div>
    </section>

    <section id="contact" class="section bg-black text-white py-16 px-4 text-center rounded-md star-animation" style="background-image: url('https://images.unsplash.com/photo-1532938311035-643d843674c1?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'); background-blend-mode: multiply; background-size: cover; background-position: center;">
        <div style="background-color: rgba(0, 0, 0, 0.9); padding: 4rem 0; border-radius: 12px;">
            <h2 class="text-4xl font-bold mb-12 text-white fade-in">Contact Us</h2>
            <p class="text-xl text-gray-300 mb-10 max-w-3xl mx-auto fade-in">Get in touch for inquiries.</p>
            <div class="contact-form max-w-md mx-auto">
                <form class="space-y-8">
                    <input type="text" placeholder="Your Name" class="w-full py-3 px-4 rounded-full border border-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent text-lg bg-gray-800 text-white">
                    <input type="email" placeholder="Your Email" class="w-full py-3 px-4 rounded-full border border-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent text-lg bg-gray-800 text-white">
                    <textarea placeholder="Your Message" rows="6" class="w-full py-3 px-4 rounded-lg border border-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent text-lg bg-gray-800 text-white"></textarea>
                    <button type="submit" class="bg-blue-500 text-white py-3 px-8 rounded-full hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent w-full text-lg transition duration-300">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-gray-300 py-8 text-center rounded-md border-t border-gray-800">
        <p class="text-lg">© 2024 Finzep. All rights reserved.</p>
    </footer>

    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        function showLoginInfo(productName) {
            alert(`Login Information for ${productName}:\nUsername: user\nPassword: password`);
        }

        function showServiceDetails(serviceType) {
            alert(`Details for ${serviceType}:\n\nMore information about our ${serviceType} services.`);
        }

        function toggleServiceDetails(listItem) {
            listItem.classList.toggle('expanded');
        }

        function showProductDetails(productName) {
            const productCard = event.target.closest('.product-card');
            if (productCard) {
                productCard.classList.toggle('expanded');
            }
        }
    </script>
</body>
</html>
<!-- partial -->
  
</body>
</html>
