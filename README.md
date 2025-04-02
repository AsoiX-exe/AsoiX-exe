<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AsoiX | Digital Kingdom</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --neon-purple: #bc13fe;
            --matrix-green: #00ff41;
            --cyber-dark: #0a0a0f;
        }

        body {
            background: var(--cyber-dark);
            color: #fff;
            font-family: 'Segoe UI', system-ui;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }

        .cyber-border {
            border: 3px solid var(--neon-purple);
            box-shadow: 0 0 15px var(--neon-purple);
            padding: 2rem;
            margin: 2rem 0;
            position: relative;
        }

        .header {
            text-align: center;
            animation: fadeIn 1.5s;
        }

        h1 {
            color: var(--neon-purple);
            font-size: 2.5rem;
            text-shadow: 0 0 10px rgba(188, 19, 254, 0.5);
            margin-bottom: 0;
        }

        .tagline {
            color: var(--matrix-green);
            font-style: italic;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin: 2rem 0;
        }

        .skill-card {
            background: rgba(10, 10, 15, 0.9);
            padding: 1.5rem;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .skill-card:hover {
            transform: translateY(-5px);
        }

        .icon {
            font-size: 1.5rem;
            margin-right: 0.5rem;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .warning {
            color: var(--matrix-green);
            border-left: 3px solid;
            padding-left: 1rem;
            margin: 2rem 0;
        }

        a {
            color: var(--neon-purple);
            text-decoration: none;
            transition: 0.3s;
        }

        a:hover {
            text-shadow: 0 0 10px var(--neon-purple);
        }
    </style>
</head>
<body>
    <div class="cyber-border">
        <header class="header">
            <h1>🖥️ AsoiX</h1>
            <p class="tagline">Code Wizard & Digital Alchemist</p>
        </header>

        <div class="skills-grid">
            <div class="skill-card">
                <h3><i class="fab fa-js icon" style="color: #f0db4f;"></i>JavaScript Sorcery</h3>
                <p>Crafting spells in the browser realm</p>
            </div>

            <div class="skill-card">
                <h3><i class="fab fa-java icon" style="color: #5382a1;"></i>Java Enchantments</h3>
                <p>Conjuring server-side magic</p>
            </div>

            <div class="skill-card">
                <h3><i class="fas fa-code icon" style="color: #e34c26;"></i>HTML/CSS Alchemy</h3>
                <p>Transforming pixels into gold</p>
            </div>
        </div>

        <div class="warning">
            <h2>⚠️ WARNING</h2>
            <p>Entering my <a href="#">GitHub Kingdom</a> may lead to:</p>
            <ul>
                <li>Code addiction 😵‍💫</li>
                <li>Sudden urge to refactor everything 🔄</li>
                <li>Matrix-like knowledge downloads 💾</li>
            </ul>
        </div>

        <footer style="text-align: center; margin-top: 2rem;">
            <p>🚀 Ready to explore? 
            <a href="#"><i class="fab fa-github"></i> Follow the White Rabbit</a></p>
        </footer>
    </div>
</body>
</html>
