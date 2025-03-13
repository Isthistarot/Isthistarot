## Hi there 👋

<!--
**Isthistarot/Isthistarot** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 👯 I’m looking to collaborate on witchcraft class that i will do soon
- 💬 Ask me about tarot/spirituality/witchcraft
- 📫 How to reach me: @isthistarot
- 😄 Pronouns: she

<!DOCTYPE html>
 <html lang="ro">
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Tarot și Servicii Esoterice</title>
     <style>
         body {
             ont-family: 'Arial', sans-serif;
             background-color: #1a1a1a;
             color: white;
             margin: 0;
             padding: 0;
             ext-align: center;
           }
 
         h1, h2 
             section {
             padding: 50px;
             border-bottom: 1px solid #444;
         }
             .tarot-card {
             width: 200px;
             height: 300px;
             background-color: #333;
             margin: 20px;
             border-radius: 15px;
             display: inline-block;
             box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
             transition: transform 0.3s;
            }
         .tarot-card:hover {
             transform: translateY(-10px);
         }
         .intro {
             background-image: url('tarot-background.jpg');
             background-size: cover;
             background-position: center;
             padding: 100px 20px;
         }
 
         .intro h1 {
             font-size: 50px;
             color: #FFD700;
         }
 
         .intro p {
             font-size: 20px;
             color: #fff;
         }
 
         .contact-form {
             background-color: rgba(0, 0, 0, 0.7);
             padding: 20px;
             border-radius: 8px;
             max-width: 500px;
             margin: 0 auto;
         }
 
         .contact-form input, .contact-form textarea {
             width: 100%;
             padding: 10px;
             margin: 10px 0;
             border: 1px solid #444;
             border-radius: 5px;
             background-color: #222;
             color: white;
         }
         .social-links {
             margin: 20px 0;
 
         .contact-form button {
             background-color: #FFD700;
             color: black;
             padding: 10px 20px;
             border: none;
             border-radius: 5px;
             cursor: pointer;
         }
             .contact-form button:hover {
             background-color: #e5c100;
         }
 
         .instagram-button {
             background-color: #E1306C;
             padding: 15px 30px;
             color: white;
             border: none;
             border-radius: 30px;
             font-size: 18px;
             text-decoration: none;
             display: inline-block;
             margin-top: 20px;
         }
             .instagram-button:hover {
             background-color: #bc135c;
         }
             .price {
             font-size: 20px;
             margin: 20px 0;
                 color: #FFD700;
         }
             .price span {
             color: #fff;
         }
 
         /* Language selector */
         .language-selector {
             position: fixed;
             top: 10px;
             right: 20px;
             background-color: #333;
             padding: 10px;
             border-radius: 5px;
             z-index: 1000;
         }
 
         .language-selector select {
             background-color: #444;
             color: white;
             border: 1px solid #555;
             padding: 5px;
             border-radius: 5px;
         }
     </style>
 </head>
 <body>
     <div class="content">
         <h1>Consultanță Tarot cu IsthisTarot</h1>
         <p>
             Bine ai venit! Sunt pasionată de divinație și tarot de mai bine de 5 ani. Citirile mele sunt 
             autentice și te pot ajuta să obții claritate în diverse aspecte ale vieții. Pentru mai multe detalii, 
             citește mai jos despre ofertele și prețurile mele.
         </p>
 
     <!-- Language selector -->
     <div class="language-selector">
         <label for="language">Language:</label>
         <select id="language" onchange="changeLanguage()">
             <option value="ro">Română</option>
             <option value="en">English</option>
         </select>
     </div>
 
     <div class="intro">
         <h1 id="title">Descoperă Magia Tarotului</h1>
         <p id="intro-text">Citiri în tarot, analize astrologice și multe altele</p>
         <a href="https://www.instagram.com/isthistarot/" class="instagram-button" target="_blank" id="instagram-button">Contactează-mă pe Instagram</a>
     </div>
 
     <div class="section">
         <h2 id="services-title">Servicii</h2>
         <div class="tarot-card"></div>
         <div class="tarot-card"></div>
         <div class="tarot-card"></div>
         
         <p id="services-description">Consultații esoterice și citiri personalizate pentru fiecare întrebare a ta.</p>
         <div class="price">
             <p><strong id="tarot-title">Citire Tarot (30 minute)</strong>: <span id="tarot-price">150 RON</span></p>
             <p><strong id="birth-chart-title">Birth Chart / Analiză Astrologică (3 întrebări + citire generală)</strong>: <span id="birth-chart-price">200 RON</span></p>
             <p><strong id="general-reading-title">Citire generală</strong>: <span id="general-reading-price">60 RON</span></p>
         </div>
         
         <a href="https://www.instagram.com/isthistarot/" class="instagram-button" target="_blank" id="ask-price">Întreabă prețul pentru tipul de citire dorit</a>
     </div>
     <div class="section">
         <h2 id="contact-title">Contact</h2>
         <div class="contact-form">
             <form>
                 <input type="text" placeholder="Nume" required>
                 <input type="email" placeholder="Email" required>
                 <textarea placeholder="Mesaj" rows="5" required></textarea>
                 <button type="submit">Trimite mesajul</button>
             </form>
         </div>
         </div>
 
     <script>
         function changeLanguage() {
             const lang = document.getElementById("language").value;
 
             if (lang === "en") {
                 document.getElementById("title").innerHTML = "Discover the Magic of Tarot";
                 document.getElementById("intro-text").innerHTML = "Tarot readings, astrology charts, and more";
                 document.getElementById("instagram-button").innerHTML = "Contact me on Instagram";
                 document.getElementById("services-title").innerHTML = "Services";
                 document.getElementById("services-description").innerHTML = "Esoteric consultations and personalized readings for every question.";
                 document.getElementById("tarot-title").innerHTML = "Tarot Reading (30 minutes)";
                 document.getElementById("tarot-price").innerHTML = "150 RON";
                 document.getElementById("birth-chart-title").innerHTML = "Birth Chart / Astrology Analysis (3 questions + general reading)";
                 document.getElementById("birth-chart-price").innerHTML = "200 RON";
                 document.getElementById("general-reading-title").innerHTML = "General Reading";
                 document.getElementById("general-reading-price").innerHTML = "60 RON";
                 document.getElementById("ask-price").innerHTML = "Ask for the price of the reading type you want";
                 document.getElementById("contact-title").innerHTML = "Contact";
                 document.querySelector('button[type="submit"]').innerHTML = "Send Message";
             } else {
                 document.getElementById("title").innerHTML = "Descoperă Magia Tarotului";
                 document.getElementById("intro-text").innerHTML = "Citiri în tarot, analize astrologice și multe altele";
                 document.getElementById("instagram-button").innerHTML = "Contactează-mă pe Instagram";
                 document.getElementById("services-title").innerHTML = "Servicii";
                 document.getElementById("services-description").innerHTML = "Consultații esoterice și citiri personalizate pentru fiecare întrebare a ta.";
                 document.getElementById("tarot-title").innerHTML = "Citire Tarot (30 minute)";
                 document.getElementById("tarot-price").innerHTML = "150 RON";
                 document.getElementById("birth-chart-title").innerHTML = "Birth Chart / Analiză Astrologică (3 întrebări + citire generală)";
                 document.getElementById("birth-chart-price").innerHTML = "200 RON";
                 document.getElementById("general-reading-title").innerHTML = "Citire generală";
                 document.getElementById("general-reading-price").innerHTML = "60 RON";
                 document.getElementById("ask-price").innerHTML = "Întreabă prețul pentru tipul de citire dorit";
                 document.getElementById("contact-title").innerHTML = "Contact";
                 document.querySelector('button[type="submit"]').innerHTML = "Trimite mesajul";
             }
         }
     </script>
 
 </body>
 </html>
