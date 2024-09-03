---
layout: default
permalink: /

speakers:
  - name: Keynote Speaker 1

  - name: Keynote Speaker 2

  - name: Keynote Speaker 3

organizers:
  - name: Christian Medeiros Adriano
    url: https://hpi.de/giese/people/christian-medeiros-adriano.html
    affiliation: Hasso Plattner Institute, University of Potsdam, Germany
    image: assets/img/christian-adriano.jpg

  - name: Sona Ghahremani
    url: https://hpi.de/en/giese/people/sona-ghahremani.html
    affiliation: Hasso Plattner Institute, University of Potsdam, Germany <br> <i>(primary contact)</i>
    image: assets/img/sona.jpg

  - name: Daiki Kimura
    url: https://researcher.watson.ibm.com/researcher/view.php?person=jp-DAIKI
    affiliation: IBM Research - Tokyo 
    image: assets/img/Daiki_Kimura.jpg

  - name: Rubén Ruiz-Torrubiano
    url: https://research.imc.ac.at/de/persons/ruben-ruiz-torrubiano
    affiliation: IMC Krems University of Applied Sciences, Austria
    image: assets/img/ruben.png


pcs:
  - name: Holger Giese
    affiliation: Hasso Plattner Institue, Germany

  - name: Steven James
    affiliation: University of the Witwatersrand, South Africa

  - name: Lucas Sakizloglou
    affiliation: Brandenburg University of Technology, German

  - name: Danilo Valerio
    affiliation: Siemens AG, Austria

---

<script>
      // Set the countdown time in seconds
      let countdown = 5;

      function startCountdown() {
          const countdownElement = document.getElementById("countdown");

          // Update the countdown every second
          const interval = setInterval(() => {
              countdown--;
              countdownElement.textContent = countdown;

              if (countdown <= 0) {
                  clearInterval(interval);
                  // Redirect to another web page
                  window.location.href = "https://conf.researchr.org/home/icse-2025/nse-2025";
              }
          }, 1000);
      }

      window.onload = startCountdown;
</script>

## Redirecting to official ICSE 2025 Workshop webpage
<center><p>You will be redirected in <span id="countdown">5</span> seconds.</p></center>

