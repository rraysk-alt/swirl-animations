<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swirl Animation</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #0f0f0f;
            overflow: hidden;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        #container {
            position: relative;
            display: flex;
            gap: 10px;
        }

        .letter {
            display: inline-block;
            font-size: 4rem;
            font-weight: bold;
            color: #00ffcc;
            text-shadow: 0 0 10px rgba(0, 255, 204, 0.5);
            transition: all 2s cubic-bezier(0.68, -0.55, 0.27, 1.55);
            position: relative;
        }

        /* The "Chaotic" State */
        .scattered {
            opacity: 0;
            transform: 
                translate(var(--x), var(--y)) 
                rotate(var(--r)) 
                scale(0.5);
            filter: blur(10px);
        }

        /* The "Formed" State */
        .formed {
            opacity: 1;
            transform: translate(0, 0) rotate(0deg) scale(1);
            filter: blur(0px);
        }
    </style>
</head>
<body>

    <div id="container"></div>

    <script>
        const text = "Terry Wak byeklo";
        const container = document.getElementById('container');

        // Initialize letters
        text.split('').forEach((char) => {
            const span = document.createElement('span');
            span.textContent = char === ' ' ? '\u00A0' : char; // Handle spaces
            span.className = 'letter scattered';
            
            // Assign random scatter values
            span.style.setProperty('--x', `${(Math.random() - 0.5) * 1000}px`);
            span.style.setProperty('--y', `${(Math.random() - 0.5) * 1000}px`);
            span.style.setProperty('--r', `${(Math.random() - 0.5) * 1080}deg`);
            
            container.appendChild(span);
        });

        const letters = document.querySelectorAll('.letter');

        function animate() {
            // Step 1: Form the words
            setTimeout(() => {
                letters.forEach(el => {
                    el.classList.remove('scattered');
                    el.classList.add('formed');
                });
            }, 500);

            // Step 2: Dissolve back
            setTimeout(() => {
                letters.forEach(el => {
                    el.classList.remove('formed');
                    el.classList.add('scattered');
                });
            }, 4000); // Stay formed for ~3.5 seconds
        }

        // Run the loop
        animate();
        setInterval(animate, 6500); // Repeat every 6.5 seconds
    </script>
</body>
</html>
