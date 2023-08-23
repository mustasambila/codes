# code for home webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hamza Traders</title>
    <!-- Link to Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Link to Tailwind CSS -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.16/dist/tailwind.min.css" rel="stylesheet">
    <!-- Link to Flowbite CSS -->
    <link href="https://cdn.jsdelivr.net/npm/flowbite@1.0.1/dist/flowbite.min.css" rel="stylesheet">
    <!-- Link to custom CSS -->
    <link rel="stylesheet" href="styles.css">
    <style>
        a{
            font-family: 'Times New Roman', Times, serif;
        }
        button{
            font-family: 'Times New Roman', Times, serif;
        }
        h1{
            font-family: 'Times New Roman', Times, serif;
        }
        p{
            font-family: 'Times New Roman', Times, serif;
        }
        h2{
            font-family: 'Times New Roman', Times, serif;
        }
        h3{
            font-family: 'Times New Roman', Times, serif;
        }
        cite{
            font-family: 'Times New Roman', Times, serif;
        }
    </style>
</head>
<body>
    <!-- Bootstrap Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Hazma Traders</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="website page.html">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="our services.html">Our Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="about us.html">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact us.html">Contact us</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Tailwind Hero Section -->
    <section class="bg-blue-600 text-white p-10">
        <div class="container mx-auto text-center">
            <h1 class="text-4xl font-bold">Welcome to Hamza Traders </h1>
            <p class="mt-4 text-lg">We provide amazing Mobile services.</p>
            <button class="bg-yellow-500 text-blue-900 hover:bg-yellow-400 hover:text-blue-800 rounded-full px-6 py-2 mt-6">Learn More</button>
        </div>
    </section>

    <!-- Flowbite Features Section -->
    <section class="py-16">
        <div class="container mx-auto">
            <h2 class="text-3xl font-semibold mb-8">Our Features</h2>
            <div class="flowbite">
                <div class="flowbite-item">
                    <div class="flowbite-icon">
                        <i class="fas fa-cogs"></i>
                    </div>
                    <div class="flowbite-text">
                        <h3 class="text-xl font-semibold">Customizable</h3>
                        <p>Our services are highly customizable to meet your needs.</p>
                    </div>
                </div>
                <!-- Add more Flowbite items as needed -->
            </div>
        </div>
    </section>

    <!-- Tailblocks Testimonials Section -->
    <section class="bg-gray-100 py-16">
        <div class="container mx-auto">
            <h2 class="text-3xl font-semibold mb-8">What Our Clients Say</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="tailblocks-testimonial">
                    <div class="tailblocks-testimonial-header">
                        <img src="image.jpg" alt="Client 1">
                    </div>
                    <div class="tailblocks-testimonial-body">
                        <p>hamza traders have very good and wellmannered staff and they are providing very and quality productsour first prefernce 
                            to buy any kind of accossories of mobile and buy or sell our mobile is hamza traders 
                        </p>
                        <cite>Client 1</cite>
                    </div>
                </div>
                <!-- Add more testimonials as needed -->
            </div>
        </div>
    </section>

    <!-- Bootstrap Footer -->
    <footer class="bg-dark text-light text-center py-4">
        <p>&copy; 2023 Hamza Traders</p>
    </footer>

   
</body>
</html>
