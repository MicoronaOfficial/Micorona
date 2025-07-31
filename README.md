<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Micorona - The Digital Micronation</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            text-align: center;
            padding: 20px 0;
            border-bottom: 2px solid #4CAF50;
        }
        h1 {
            color: #2E8B57;
        }
        .flag {
            height: 120px;
            width: 200px;
            background: linear-gradient(to bottom, #4CAF50 50%, #FFD700 50%);
            margin: 10px auto;
            border: 1px solid #333;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }
        .join-btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .join-btn:hover {
            background-color: #45a049;
        }
        section {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            margin-top: 30px;
            color: #666;
            font-size: 0.9em;
        }
        .anthem-player {
            text-align: center;
            margin: 20px 0;
            padding: 15px;
            background-color: #f0f8ff;
            border-radius: 8px;
        }
        .anthem-note {
            font-size: 0.8em;
            color: #666;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="flag"></div>
        <h1>✨ The Sovereign Micronation of Micorona ✨</h1>
        <p><em>"In God We Trust, In Bitcoin We Prosper"</em></p>
    </header>

    <section>
        <h2>National Anthem</h2>
        <div class="anthem-player">
            <h3>Micorona National Anthem</h3>
            <p>(Currently using The Star-Spangled Banner as placeholder)</p>
            <audio controls>
                <source src="https://www.usnationalanthem.org/wp-content/uploads/2017/03/The-United-States-National-Anthem.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <p class="anthem-note">Note: This is a temporary anthem until the official Micorona National Anthem is composed. Citizens may submit anthem proposals to the Ministry of Culture.</p>
        </div>
    </section>

    <section>
        <h2>About Our Nation</h2>
        <p><strong>Version 0.3</strong> - Last updated: <span id="currentDate"></span></p>
        <p>Micorona is a thriving digital micronation established in 2024. While our physical territory currently resides within a private residence, our digital presence spans the globe.</p>
        <p>Founded on principles of innovation and self-governance, we may not yet have a physical flag, but our spirit flies high in the digital realm!</p>
    </section>

    <section>
        <h2>National Information</h2>
        <h3>Official Currency</h3>
        <p>💰 Bitcoin (BTC) - The world's first decentralized digital currency</p>
        
        <h3>Official Languages</h3>
        <p>🗣️ English (Primary)<br>
        🗣️ Micoronese (Under development)</p>
        
        <h3>Government Type</h3>
        <p>🏛️ Digital Constitutional Monarchy (Provisional)</p>
    </section>

    <section>
        <h2>Citizenship Opportunities</h2>
        <p>We're currently accepting applications for our Founding Citizen program!</p>
        <p>Benefits include:</p>
        <ul>
            <li>🏆 Founding Citizen status</li>
            <li>📜 Digital Certificate of Citizenship</li>
            <li>💬 Access to our national Discord community</li>
            <li>🪙 Future airdrops of MICO tokens</li>
        </ul>
        <div style="text-align: center; margin: 20px 0;">
            <a href="mailto:Radfordkurtis49@gmail.com?subject=Micorona Citizenship Application">
                <button class="join-btn">Apply for Citizenship NOW!</button>
            </a>
        </div>
    </section>

    <footer>
        <h3>Long Live Micorona!</h3>
        <p>© 2024 The Provisional Government of Micorona<br>
        All rights reserved - A micronation in development</p>
    </footer>

    <script>
        // Add current date automatically
        document.getElementById('currentDate').textContent = new Date().toLocaleDateString();
    </script>
</body>
</html>
