<!DOCTYPE html>
<html lang="hu">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AEGIS Drone Services - Légi felderítés, geoinformatika és biztonsági megoldások</title>
  
  <style>
    body { margin: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: #f4f6f8; color: #1a1a1a; line-height: 1.6; }
    header { background: #0a1a2a; color: white; padding: 40px 20px; text-align: center; position: relative; }
    header .logo { position: absolute; left: 20px; top: 20px; width: 80px; height: 80px; }
    header h1 { margin: 0; font-size: 2.8rem; letter-spacing: 1px; }
    header p { font-size: 1.2rem; margin-top: 10px; font-weight: 300; }
    nav { background: #112d42; padding: 15px; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.2); }
    nav a { color: #fff; margin: 0 20px; text-decoration: none; font-weight: bold; font-size: 1rem; transition: color 0.3s ease; }
    nav a:hover { color: #5cb85c; }
    .section { padding: 80px 20px; max-width: 1200px; margin: auto; }
    h2 { border-left: 6px solid #5cb85c; padding-left: 15px; font-size: 2.2rem; margin-bottom: 40px; color: #0a1a2a; }
    .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
    .card { background: white; padding: 30px; border-radius: 12px; box-shadow: 0 6px 20px rgba(0,0,0,0.1); transition: transform 0.3s ease, box-shadow 0.3s ease; }
    .card:hover { transform: translateY(-5px); box-shadow: 0 10px 30px rgba(0,0,0,0.15); }
    .card h3 { margin-top: 0; color: #0a1a2a; font-size: 1.5rem; }
    .card img { max-width: 100%; height: auto; border-radius: 8px; margin-bottom: 15px; }
    footer { background: #0a1a2a; color: white; text-align: center; padding: 30px; margin-top: 60px; }

    /* Kontakt űrlap stílus */
    .contact-box { background: white; padding: 40px; border-radius: 12px; box-shadow: 0 6px 20px rgba(0,0,0,0.1); max-width: 700px; margin: auto; }
    .contact-box form { display: grid; gap: 20px; }
    .contact-box label { font-weight: bold; color: #333; }
    .contact-box input[type="text"],
    .contact-box input[type="email"],
    .contact-box input[type="tel"],
    .contact-box textarea,
    .contact-box select {
      width: 100%;
      padding: 12px;
      border: 1px solid #ddd;
      border-radius: 6px;
      font-size: 1rem;
      box-sizing: border-box; /* Padding nem növeli a szélességet */
    }
    .contact-box textarea { resize: vertical; min-height: 120px; }
    .contact-box button {
      background: #5cb85c;
      color: white;
      padding: 15px 25px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1.1rem;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }
    .contact-box button:hover { background: #4cae4c; }

    /* Üzenetküldés visszajelzés */
    #form-message {
      margin-top: 20px;
      padding: 15px;
      border-radius: 8px;
      display: none; /* Alapból rejtett */
    }
    #form-message.success { background-color: #dff0d8; color: #3c763d; border: 1px solid #d6e9c6; }
    #form-message.error { background-color: #f2dede; color: #a94442; border: 1px solid #ebccd1; }

    /* Ingatlan értékesítés specifikus stílus */
    .real-estate-card {
        background: #e8f5e9; /* Világosabb háttér a kiemeléshez */
        padding: 30px;
        border-radius: 12px;
        box-shadow: 0 6px 20px rgba(0,0,0,0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        border: 2px solid #5cb85c; /* Kiemelő szegély */
    }
    .real-estate-card:hover { transform: translateY(-5px); box-shadow: 0 10px 30px rgba(0,0,0,0.15); }
    .real-estate-card h3 { color: #2e7d32; } /* Sötétebb zöld cím */
  </style>
</head>
<body>
  <header>
    <!— Cég logó —>
    
    <h1>AEGIS Drone Services</h1>
    <p>Aerial Enforcement & Geo-Intelligence Services – Légi felderítés, geoinformatika és biztonsági megoldások</p>
  </header>

  <nav>
    <a href="#szolgaltatasok">Szolgáltatások</a>
    <a href="#ingatlan">Ingatlan Értékesítés</a>
    <a href="#miertmi">Miért Mi?</a>
    <a href="#flotta">Flotta</a>
    <a href="#kapcsolat">Kapcsolat</a>
  </nav>

  <section class="section" id="szolgaltatasok">
    <h2>Szolgáltatásaink</h2>
    <div class="cards">
      <div class="card">
        <h3>Hőkamerás Épületdiagnosztika</h3>
        
        <p>Hőhidak, szigetelési hiányosságok, beázások és energetikai problémák drónos felmérése hőkamerával. Pontos hibafeltárás a fűtési költségek csökkentéséért.</p>
      </div>
      <div class="card">
        <h3>Precíziós Napelem Vizsgálat</h3>
        
        <p>Drónos termográfia a napelem parkok és tetőre szerelt rendszerek hot spotjainak, hibás celláinak azonosítására. Maximalizálja a hozamot és garantálja a rendszer optimális működését.</p>
      </div>
      <div class="card">
        <h3>Légtömörség Vizsgálat (Blower Door Test)</h3>
        
        <p>A hőkamerás mérések kiegészítése légtömörség-vizsgálattal. Feltárjuk a rejtett légszivárgásokat, huzatos pontokat, ezzel is hozzájárulva az épület energiahatékonyságához.</p>
      </div>
      <div class="card">
        <h3>Ipari Infrastruktúra Audit</h3>
        
        <p>Hidromorfikus térképezés, 3D modellezés, ipari kémények és magas építmények állapotfelmérése. Részletes dokumentáció a megelőző karbantartáshoz.</p>
      </div>
    </div>
  </section>

  <section class="section" id="ingatlan">
    <h2>Drónokkal több siker az ingatlan értékesítésben!</h2>
    <div class="cards">
      <div class="real-estate-card">
        <h3>Emelje ki ingatlanát a tömegből!</h3>
        
        <p>Lenyűgöző légifelvételek, 4K videók és interaktív 3D modellek készítése ingatlanokról. Segítünk, hogy a potenciális vevők már az első pillanatban beleszeressenek az eladó házba, telekbe vagy lakásba.</p>
        <p><strong>Növelje az érdeklődők számát és gyorsítsa fel az értékesítést professzionális drónos marketinganyagokkal!</strong></p>
      </div>
      <div class="card">
        <h3>Miért válassza ezt a kiegészítő szolgáltatást?</h3>
        <ul>
          <li>**Páratlan vizuális élmény:** Teljes perspektívát ad a környékről, a telekről és az épületről.</li>
          <li>**Magasabb eladási ár:** A profi prezentáció emeli az ingatlan értékét.</li>
          <li>**Gyorsabb értékesítés:** Az egyedi képek és videók felkeltik a figyelmet.</li>
          <li>**Különbségtétel:** Tűnjön ki a hirdetések tengeréből!</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="section" id="miertmi">
    <h2>Miért válasszon minket?</h2>
    <div class="cards">
      <div class="card">
        <h3>Rendészeti háttér és precizitás</h3>
        <p>Több éves operatív és vezetői tapasztalat a biztonság, dokumentáció és eljárásrendek területén. Ez garantálja a pontos, megbízható adatgyűjtést és elemzést.</p>
      </div>
      <div class="card">
        <h3>Teljes körű jogszabályi megfelelés</h3>
        <p>Magas szintű ismeret a repülési és adatkezelési szabályokról (pl. A2 vizsga). Minden műveletet a hatályos előírások szerint, biztonságosan és jogszerűen végzünk.</p>
      </div>
      <div class="card">
        <h3>Professzionális, ipari technológia</h3>
        <p>Modern drónflottánk (DJI Mavic 3 Thermal) garantálja a kiemelkedő felbontású vizuális és termikus adatok gyűjtését, auditálható riportok és eredmények formájában.</p>
      </div>
    </div>
  </section>

  <section class="section" id="flotta">
    <h2>Drónflottánk – Technológia a Precizitásért</h2>
    <div class="cards">
      <div class="card">
        <h3>DJI Mavic 3 Thermal (M3T)</h3>
        
        <p>A legmodernebb ipari drónunk, mely 48MP-es vizuális kamerával és 640x512 felbontású hőkamerával rendelkezik. Ideális választás komplex épületdiagnosztikához és napelemvizsgálathoz, nagy területek gyors és pontos felmérésére.</p>
      </div>
      <div class="card">
        <h3>DJI Mini 4 Pro (Kiegészítő)</h3>
        
        <p>Rugalmas, alacsony-kockázatú műveletekhez, ahol a vizuális dokumentáció a prioritás. Precíz fotogrammetria és 4K HDR videók készítésére alkalmas, szűkebb helyeken is kiválóan alkalmazható.</p>
      </div>
      <div class="card">
        <h3>Kiegészítő Mérőeszközök</h3>
        
        <p>A drónflotta mellett korszerű Blower Door tesztkészlettel és egyéb kézi hőkamerákkal rendelkezünk a pontosabb helyszíni diagnosztikához és a komplex problémák feltárásához.</p>
      </div>
    </div>
  </section>

  <section class="section" id="kapcsolat">
    <h2>Kapcsolat</h2>

    <div class="contact-box">
      <p>Kérjük, töltse ki az alábbi űrlapot, és felvesszük Önnel a kapcsolatot 24 órán belül.</p>
      <form id="contact-form">
        <label for="name">Név:*</label>
        <input type="text" id="name" name="name" required>

        <label for="email">E-mail cím:*</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Telefonszám:</label>
        <input type="tel" id="phone" name="phone">

        <label for="service">Érdeklődés tárgya:*</label>
        <select id="service" name="service" required>
          <option value="">-- Kérjük, válasszon --</option>
          <option value="hokamera">Hőkamerás Épületdiagnosztika</option>
          <option value="napelem">Napelem Vizsgálat</option>
          <option value="ingatlan">Ingatlan Légi Fotózás/Videózás</option>
          <option value="ipari">Ipari Infrastruktúra Audit</option>
          <option value="mas">Egyéb / Részletes Ajánlatkérés</option>
        </select>

        <label for="message">Üzenet / Projekt részletei:*</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Üzenet küldése</button>
      </form>
      <div id="form-message"></div> <p style="margin-top: 30px;"><strong>E-mail:</strong> aegis.drone@gmail.com</p>
      <p><strong>Telefon:</strong> +36 30 374 4716</p>
      <p><strong>Székhely:</strong> Budapest</p>
    </div>
  </section>

  <footer>
    <p>© 2025 AEGIS Drone Services – Minden jog fenntartva.</p>
  </footer>

  <script>
    document.getElementById('contact-form').addEventListener('submit', function(event) {
      event.preventDefault(); // Megakadályozza az űrlap alapértelmezett elküldését

      const formMessage = document.getElementById('form-message');
      formMessage.style.display = 'block'; // Láthatóvá teszi az üzenetdobozt

      // It küldené el az adatokat egy szerverre (pl. fetch API-val vagy XMLHttpRequest-tel)
      // Mivel ez egy frontend only demó, csak egy sikeres üzenetet jelenítünk meg.
      // Egy valós alkalmazásban itt lenne a szerveroldali logika.

      setTimeout(() => {
        formMessage.classList.remove('error');
        formMessage.classList.add('success');
        formMessage.textContent = 'Köszönjük üzenetét! Hamarosan felvesszük Önnel a kapcsolatot.';
        document.getElementById('contact-form').reset(); // Űrlap ürítése
      }, 1000); // 1 másodperc múlva jelenik meg a sikerüzenet
      
      // Hiba esetén (pl. ha a szerver 500-as hibát küld):
      /*
      setTimeout(() => {
        formMessage.classList.remove('success');
        formMessage.classList.add('error');
        formMessage.textContent = 'Hiba történt az üzenet küldése során. Kérjük, próbálja újra később, vagy vegye fel velünk a kapcsolatot közvetlenül.';
      }, 1000);
      */
    });
  </script>
</body>
</html>
