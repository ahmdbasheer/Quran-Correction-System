
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Quran Recitation Correction System">
    <title>Quran Recitation Correction System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 1rem 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .features {
            margin: 2rem 0;
        }
        .features h2 {
            color: #4CAF50;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            margin: 0.5rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Quran Recitation Correction System</h1>
        <p>A standalone system for improving Quranic recitation with real-time feedback</p>
    </header>

    <nav>
        <a href="#features">Features</a>
        <a href="#how-it-works">How It Works</a>
        <a href="#components">System Components</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="features">
            <h2>Features</h2>
            <ul>
                <li>Real-time correction of Quranic recitation errors</li>
                <li>Detection of pronunciation and Tajweed mistakes</li>
                <li>Assistance with memorization of Quranic verses</li>
                <li>Portable and user-friendly standalone system</li>
            </ul>
        </section>

        <section id="how-it-works">
            <h2>How It Works</h2>
            <p>The Quran Recitation Correction System captures the user's recitation using a microphone. The recitation is processed by the ESP32 microcontroller, which performs speech-to-text conversion and error detection. The system compares the recitation with Quranic verses stored in an SD card, identifies mistakes, and provides corrective feedback through a display and speaker.</p>
        </section>

        <section id="components">
            <h2>System Components</h2>
            <ul>
                <li><strong>ESP32 Microcontroller:</strong> Processes recitation and manages feedback.</li>
                <li><strong>Microphone Module:</strong> Captures user recitation.</li>
                <li><strong>OLED Display:</strong> Provides visual feedback.</li>
                <li><strong>SD Card Module:</strong> Stores Quranic verses and Tajweed rules.</li>
                <li><strong>Speaker:</strong> Delivers auditory feedback.</li>
                <li><strong>Power Supply:</strong> Ensures portability with battery support.</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>For inquiries, email us at <a href="mailto:contact@quransystem.com" style="color: #4CAF50;">contact@quransystem.com</a></p>
    </footer>
</body>
</html>
