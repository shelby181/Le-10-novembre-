# Le-10-novembre-
Rien que pour toi ma puce ❤🫂
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>10 Novembre ❤️</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: #100b13;
  color: #fff;
  font-family: Georgia, serif;
  text-align: center;
  overflow-x: hidden;
}

section {
  min-height: 100vh;
  padding: 75px 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

h1 {
  color: #ff8eae;
  font-size: 35px;
  margin-bottom: 20px;
}

h2 {
  color: #ff9db9;
  margin-bottom: 20px;
}

p {
  max-width: 550px;
  line-height: 1.9;
  color: #e8dce4;
  font-size: 17px;
}

button {
  background: linear-gradient(135deg, #ff477e, #c72d69);
  border: none;
  padding: 14px 27px;
  color: white;
  border-radius: 30px;
  font-size: 16px;
  margin-top: 25px;
  cursor: pointer;
  box-shadow: 0 0 20px #ff477e55;
}

button:active {
  transform: scale(.95);
}

.hidden {
  display: none;
}

.heart {
  position: fixed;
  bottom: -30px;
  color: #ff6b91;
  animation: fly 6s linear forwards;
  pointer-events: none;
  z-index: 10;
}

@keyframes fly {
  to {
    transform: translateY(-110vh) rotate(360deg);
    opacity: 0;
  }
}

.card {
  background: #211522;
  border: 1px solid #75405c;
  border-radius: 20px;
  padding: 25px;
  max-width: 500px;
  width: 100%;
  margin: 15px auto;
  box-shadow: 0 0 25px #ff477e18;
}

input {
  background: #2a1b2d;
  border: 1px solid #ff8eae;
  padding: 13px;
  border-radius: 10px;
  color: white;
  text-align: center;
  font-size: 17px;
  margin-top: 20px;
  width: 220px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px;
  max-width: 500px;
  width: 100%;
  margin-top: 20px;
}

.gallery div {
  background: #291b2d;
  padding: 25px 10px;
  border-radius: 15px;
  border: 1px solid #71445d;
}

.gallery span {
  font-size: 35px;
  display: block;
  margin-bottom: 10px;
}

#finalMessage {
  animation: appear 2s ease;
}

@keyframes appear {
  from {opacity: 0; transform: translateY(30px);}
  to {opacity: 1; transform: translateY(0);}
}

footer {
  padding: 30px;
  color: #a58b9b;
}
</style>
</head>

<body>

<!-- ACCUEIL -->
<section id="debut">
  <p>Une petite invitation...</p>
  <h1>10 Novembre ❤️</h1>
  <p>
    Il existe des surprises qu'on ne peut pas expliquer
    avant de les découvrir.
  </p>
  <button id="entrer">Découvrir mon cadeau ✨</button>
</section>

<!-- ACCUEIL PERSONNEL -->
<section id="accueil" class="hidden">
  <h1>Bienvenue dans ton univers ❤️</h1>
  <p>
    Aujourd'hui, j'ai préparé quelque chose de spécial.
    Prends ton temps, chaque détail a sa petite histoire.
  </p>
  <button id="commencer">Je suis prête 💌</button>
</section>

<!-- CODE SECRET -->
<section id="codeSection" class="hidden">
  <div class="card">
    <h2>🔐 Un petit secret...</h2>
    <p>
      Pour continuer, tu dois retrouver notre date spéciale.
    </p>
    <input id="code" type="password" placeholder="Code secret">
    <br>
    <button id="verifierCode">Déverrouiller ❤️</button>
    <p id="erreur" class="hidden">Essaie encore, mon amour. ❤️</p>
  </div>
</section>

<!-- SOUVENIRS -->
<section id="souvenirs" class="hidden">
  <h1>Nos petits souvenirs 🥹</h1>
  <p>
    Certaines dates sont devenues des souvenirs
    que je ne voudrais jamais oublier.
  </p>

  <div class="card">
    <h2>06 Juillet 2026</h2>
    <p>Le début d'un nouveau chapitre...</p>
  </div>

  <div class="card">
    <h2>07 Juillet 2026</h2>
    <p>Un jour qui nous rapprochait sans qu'on le sache.</p>
  </div>

  <div class="card">
    <h2>10 Juillet 2026</h2>
    <p>Un moment qui occupe une place particulière dans mon cœur. ❤️</p>
  </div>

  <button id="versGalerie">Continuer 🌹</button>
</section>

<!-- GALERIE -->
<section id="galerie" class="hidden">
  <h1>Une histoire en images 📸</h1>
  <p>
    Chaque photo pourra raconter un petit morceau
    de notre histoire.
  </p>

  <div class="gallery">
    <div><span>❤️</span>Notre complicité</div>
    <div><span>🥰</span>Nos sourires</div>
    <div><span>🌹</span>Nos moments</div>
    <div><span>💍</span>Nos rêves</div>
  </div>

  <button id="versLettre">J'ai encore quelque chose pour toi 💌</button>
</section>

<!-- LETTRE -->
<section id="lettreSection" class="hidden">
  <h1>Une lettre pour toi 💌</h1>

  <div class="card">
    <p>
      Je ne sais pas toujours trouver les mots parfaits,
      mais je sais une chose : ta présence donne une
      valeur particulière à beaucoup de mes journées.
      <br><br>
      Je veux continuer à construire de beaux souvenirs,
      apprendre, grandir et avancer avec toi.
      <br><br>
      Merci d'être cette personne qui occupe une place
      si particulière dans mon cœur.
      <br><br>
      Cette petite surprise est simplement une façon
      de te rappeler que tu comptes énormément pour moi.
      ❤️
    </p>
  </div>

  <button id="boutonFinal">Il reste une dernière chose... 🥹</button>
</section>

<!-- SURPRISE FINALE -->
<section id="finalSection" class="hidden">
  <div id="finalMessage">
    <h1>Pour toi, Manmi ❤️</h1>
    <h2>Si c'était à refaire...</h2>

    <p>
      Je choisirais encore de découvrir ton sourire,
      de partager des moments avec toi et d'écrire
      cette histoire à tes côtés.
      <br><br>
      Je ne promets pas une histoire parfaite,
      mais je souhaite une histoire sincère,
      remplie de respect, de patience et d'amour.
      <br><br>
      Et surtout, je veux que tu n'oublies jamais
      combien tu es précieuse.
      <br><br>
      <strong>Avec tout mon amour. ❤️</strong>
    </p>
  </div>

  <h1 style="margin-top:35px;">❤️ ∞ ❤️</h1>
</section>

<footer>
  Créé avec amour ❤️ | 10.11.2026
</footer>

<script>
document.addEventListener("DOMContentLoaded", function() {

  function afficher(id) {
    document.querySelectorAll("section").forEach(function(section) {
      section.classList.add("hidden");
    });

    document.getElementById(id).classList.remove("hidden");
    window.scrollTo({top: 0, behavior: "smooth"});
  }

  document.getElementById("entrer").addEventListener("click", function() {
    afficher("accueil");
  });

  document.getElementById("commencer").addEventListener("click", function() {
    afficher("codeSection");
  });

  document.getElementById("verifierCode").addEventListener("click", function() {
    let code = document.getElementById("code").value.trim();

    if (code === "1007") {
      afficher("souvenirs");
    } else {
      document.getElementById("erreur").classList.remove("hidden");
    }
  });

  document.getElementById("versGalerie").addEventListener("click", function() {
    afficher("galerie");
  });

  document.getElementById("versLettre").addEventListener("click", function() {
    afficher("lettreSection");
  });

  document.getElementById("boutonFinal").addEventListener("click", function() {
    afficher("finalSection");
    lancerCoeurs();
  });

  function lancerCoeurs() {
    for (let i = 0; i < 35; i++) {
      let coeur = document.createElement("div");
      coeur.className = "heart";
      coeur.innerHTML = "❤";
      coeur.style.left = Math.random() * 100 + "vw";
      coeur.style.animationDelay = Math.random() * 3 + "s";
      coeur.style.fontSize = (15 + Math.random() * 25) + "px";

      document.body.appendChild(coeur);

      setTimeout(function() {
        coeur.remove();
      }, 9000);
    }
  }

});
</script>

</body>
</html>
