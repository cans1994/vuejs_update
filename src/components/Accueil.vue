<template>
    
    <nav>
        <div id="plop">
        <h1>Générateur de CV</h1>
        <img alt="carte du monde" src="@/assets/job.jpg"/>
        </div>

        <section id="enTete">
        <div class="container">
        
        <p>S'inscrire gratuitement : </p> 
        <button class="EnSavoirPlus"> <a href="#savoir_plus">En savoir plus</a></button>
        <h2>Comment ça marche, les 8 Fantastiques ?</h2>
        <p>Nous simplifions le parcours à un niveau inégalé</p>
        </div>
        </section>
        <section id="Parcours">
            <div class="un">
                <h1><button class="h1">1</button></h1>
                <p>
                    Créer moi-même mon CV
                    et le télécharger en PDF,
                    ou en version web
                </p>
            </div>
            <div class="un">
                <h1><button class="h1">2</button></h1>
                <p>
                    Me faire remarquer
                    en un seul clic
                </p>
            </div>
            <div class="un">
                <h1><button class="h1">3</button></h1>
                <p>
                    Trouver des offres d’emploi
                    qui me correspondent,
                    postuler et m’organiser
                </p>
            </div>
        </section>
         <div class="accueil">
                <h1>Les 8 Fantastiques</h1>
                <div class="slogan">
                    <p>"You can't save the world alone."</p>
                </div>

                <div class=presentation>
                    <div id="savoir_plus">
                    <h2> En savoir plus :</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                            Asperiores, optio deleniti! Aliquam fugiat expedita, accusantium quae quasi eligendi
                            ex perspiciatis quas vel inventore repudiandae dicta sunt perferendis cum blanditiis
                            veritatis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo vero, soluta
                            sunt quibusdam cumque cupiditate tempore molestiae quas natus dolorum eveniet recusandae!
                            Voluptates
                            sed dolorum at sunt numquam accusantium harum.</p>
                    </div>
                </div>
                <div class="description">
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Asperiores, optio deleniti! Aliquam fugiat expedita, accusantium quae quasi eligendi
                        ex perspiciatis quas vel inventore repudiandae dicta sunt perferendis cum blanditiis
                        veritatis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo vero, soluta
                        sunt quibusdam cumque cupiditate tempore molestiae quas natus dolorum eveniet recusandae!
                        Voluptates
                        sed dolorum at sunt numquam accusantium harum.</p>
                </div>
                <div class="description2">
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Asperiores, optio deleniti! Aliquam fugiat expedita, accusantium quae quasi eligendi
                        ex perspiciatis quas vel inventore repudiandae dicta sunt perferendis cum blanditiis
                        veritatis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo vero, soluta
                        sunt quibusdam cumque cupiditate tempore molestiae quas natus dolorum eveniet recusandae!
                        Voluptates
                        sed dolorum at sunt numquam accusantium harum.</p>
                </div>
            </div>
    </nav>
</template>

<script>

</script>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Staatliches&display=swap');

*{
background: rgb(59, 86, 97);
    font-family: 'Staatliches', cursive;
    justify-content: space-between;
    color: white;
    margin: 5%;
}

img {
    width: 80%;
    height: 600px;
}
body {
  font-family: 'Staatliches', cursive;
  color: white;
}

a {
  color: #34b7a7;
  text-decoration: none;
}

a:hover {
  color: #51cdbe;
  text-decoration: none;
}

.container {
    font-size: 1em;
}

.EnSavoirPlus {
    font-size: 1em;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Staatliches', cursive;
  padding: 1%;
}

.un {
    padding: 0;
    margin: 0;
    text-align: center;
}

.un p{
    margin-top: 50px;
    margin-bottom: 60px;
}


.description {
    margin: 10%;
    text-align: center;
}

.description2 {
    margin: 10%;
    text-align: center;
    padding-bottom: 20%;
}

.presentation {
  color: white;
  padding: 10%;
}
#main {
  margin-top: 50px;
}

</style>


