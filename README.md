<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Game Development Portfolio</title>
    <style>
        /* Inline CSS for the font and other styles */
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }
        
        /* Rest of your inline CSS styles */
        /* ... (previous styles) ... */
    </style>
</head>
<body>
    <header style="background-color: #333; color: #fff; text-align: center; padding: 20px;">
        <h1 style="font-size: 2rem;">Welcome to My Game Development Portfolio!</h1>
    </header>

    <main style="max-width: 800px; margin: 0 auto; padding: 20px; background-color: #fff; box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1); border-radius: 5px;">
        <!-- ... (previous sections) ... -->
    </main>

    <footer style="background-color: #333; color: #fff; text-align: center; padding: 10px;">
        <!-- Add your contact information or links to your social profiles here -->
    </footer>

    <script>
        // JavaScript for a simple fade-in effect on scroll
        window.addEventListener('scroll', function() {
            const main = document.querySelector('main');

            // Fade-in effect for main content
            const mainPosition = main.getBoundingClientRect().top;
            const windowHeight = window.innerHeight;
            if (mainPosition < windowHeight * 0.75) {
                main.style.opacity = 1;
            }
        });
    </script>
</body>
</html>
