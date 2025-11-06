# ipl
Imperials Web


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Imperials Guild - Official Homepage</title>
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
    <div class="bg-animation"></div>

    <!-- Navigation -->
    <nav>
        <img src="https://img.recraft.ai/esTRdlS2AlLQZOFSDpfKdn7_oMnjp1d-Q5M6GWqsrsA/raw:1/plain/abs://prod/images/4277a09e-c4e7-4da1-ad48-6bd395ca82a4" alt="Imperials IPL" class="logo">
        <ul class="nav-links">
            <li><a href="index.html">Home</a></li>
            <li><a href="https://discord.gg/4XG9NFEW">Discord</a></li>
            <li><a href="https://sao-minecraft-ku9a.vercel.app/menu.html">Wiki</a></li>
            <li><a href="membres.html">Membres</a></li>
            <li><a href="histoire.html">Histoire</a></li>
            <li><a href="home.html">Services</a></li>
        </ul>
    </nav>

    


    



    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Imperials IPL. All rights reserved.</p>
        <p>Dominating the esports arena.</p>
    </footer>
    
    </body>
    </html>





     gradeDiv.innerHTML = `
      <div class="grade-title" style="background: ${grade.color}; -webkit-background-clip: text; color: transparent;">
        <span>${grade.icon}</span> ${grade.name}
      </div>
      <div class="carousel">
        ${membersByGrade.map((member) => `
          <div class="member-card">
            <img
              src="https://visage.surgeplay.com/face/128/${member.pseudo}"
              onerror="this.src='https://visage.surgeplay.com/face/128/Steve';"
              alt="${member.pseudo}"
            >
            <p>${member.pseudo}</p>
          </div>
        `).join('')}
      </div>
    `;






    <style>
  .grade-block {
    margin: 4rem 0;
    text-align: center;
  }

  .grade-title {
    font-size: 2rem;
    font-weight: bold;
    margin-bottom: 1.5rem;
    text-transform: uppercase;
    letter-spacing: 1px;
  }

  /* Conteneur global fluide */
  .carousel {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
    max-width: 1000px;
    margin: 0 auto;
  }

  .member-card {
    background: linear-gradient(135deg, rgba(20, 20, 30, 0.8), rgba(40, 20, 50, 0.6));
    border: 2px solid rgba(236, 72, 153, 0.3);
    border-radius: 12px;
    width: 100px;
    padding: 0.5rem;
    text-align: center;
    box-shadow: 0 4px 15px rgba(236, 72, 153, 0.2);
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .member-card:hover {
    transform: translateY(-5px) scale(1.05);
    box-shadow: 0 8px 20px rgba(236, 72, 153, 0.4);
  }

  .member-card img {
    width: 80px;
    height: 80px;
    border-radius: 10px;
    margin-bottom: 0.4rem;
  }

  .member-card p {
    color: #fff;
    font-weight: 600;
    font-size: 0.8rem;
    word-break: break-all;
  }

  /* Responsive */
  @media (max-width: 768px) {
    .member-card {
      width: 80px;
      padding: 0.4rem;
    }

    .member-card img {
      width: 60px;
      height: 60px;
    }

    .member-card p {
      font-size: 0.7rem;
    }
  }

    /* Pour que l'émojo soit complet*/
  .emoji {
     background: none !important;
    -webkit-background-clip: initial !important;
    color: initial !important;
    margin-right: 6px;
    background-clip: text; /* standard (très peu supporté) */
    -webkit-background-clip: text; /* Chrome, Safari, Edge */

}

    </style>



    <a href="https://sao-minecraft-ku9a.vercel.app/menu.html" class="cta-button">Wiki</a>