<template>
  <div id="about" class="p-5 my-5 container text-start h-100 justify-content-between shadow-sm">
    <div class="row p-5 my-5">
      <h2 class="text-center fw-bolder">About the collection</h2>
      <div class="row p-3 align-items-center" data-aos="fade-right">
        <div class="col-md-5 col-12 p-2 py-5 text-center">
          <div class="avatar">
            <img
              class="img-fluid animate text-white opacity-50"
              src="https://i.postimg.cc/85nqKpBs/imagebackground.jpg"
              alt="my image"
            />
          </div>
        </div>
        <div class="col-md-6 col-12 myself con" data-aos="zoom-in-up" data-aos-easing="ease-in">
          <p class="text-black myself std soft">
            Welcome to Voices of the African Pastoral Landscape. This digital collection presents an intimate look at four key animals—horses, cows, sheep, 
            and goats—that are deeply intertwined with the pastoral and agricultural traditions across Africa. Each of these animals holds unique significance 
            in African culture, whether as companions, sources of sustenance, or symbols within local stories and rituals.

Through both imagery and audio recordings, this collection aims to celebrate the voices and presence of these animals. 
By focusing on these sounds and scenes, we invite viewers to consider the nuanced relationships between humans and animals in Africa, moving away from often simplified Western narratives of domestication or agricultural labor. Instead, this collection offers an opportunity to explore African perspectives on kinship, respect, and 
coexistence with animals in ways that challenge colonial interpretations of agriculture and animal husbandry.</p>
          <div class="row text-center m-auto">
            <div class="col">
              <button class="btn">Hourses</button>
              <button class="btn">Cows</button>
              <button class="btn">Goat</button>
              <button class="btn">Sheep</button>
              <button class="btn">Goat-Sound</button>
              <button class="btn">Cow-Sound</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutView",
};
</script>

<style scoped>
* {
  font-family: Raleway, sans-serif;
}

@import url("https://fonts.googleapis.com/css2?family=Alkalami&family=Gemunu+Libre:wght@300;400;800&family=Shadows+Into+Light&display=swap");

/* Add padding to the top of the #about section to avoid overlap */
#about {
  padding-top: 100px; /* Adjust based on navbar height */
}

/* Responsive row styling */
.row {
  color: #898989;
  font-family: "Lucida Console", "Courier New", monospace;
  font-size: 15px;
  font-weight: 300;
  line-height: 20px;
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
}

img {
  border-radius: 10px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.3);
  max-height: 400px;
  width: 100%;
}

.text-container button {
  width: 130px;
  height: 42px;
  border-radius: 12px;
  font-weight: 500;
  outline: none;
  margin: 10px;
}

.con {
  background: linear-gradient(95deg, #d49828, hsla(34, 78%, 49%, 0.773), hsla(41, 83%, 46%, 0.305), #d0b966);
  height: auto;
  padding: 20px;
  margin: auto;
}

.std {
  padding: 5px;
  text-align: justify;
  font-size: 1em;
  font-family: 'Gill Sans', 'Gill Sans MT';
  color: #000;
  font-weight: 500;
}

h2 {
  font-size: 2.2em;
  margin-top: 40px;
  text-align: center;
  color: #545f5d;
  font-weight: 500;
  text-shadow: 1px 1px 1px #000, 3px 3px 5px rgb(224, 138, 18);
}

.btn {
  border: 2px solid #000;
  width: 11em;
  height: 2.4em;
  font-family: Oxygen, sans-serif;
  font-size: 16px;
  box-shadow: 0px 0px 15px 3px rgba(15, 15, 15, 0.3);
  color: #fff;
  background-color: #2c3e50;
  border-radius: 4px;
  transition: border 200ms ease-in-out, background-color 200ms ease-in-out;
  cursor: pointer;
  margin-top: 10px;
}

.btn:hover {
  border-width: 4px;
  background-color: transparent;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  h2 {
    font-size: 1.8em;
  }

  .con {
    width: 100%;
    padding: 10px;
  }

  .avatar img {
    max-height: 300px;
  }

  .btn {
    width: 100%;
    margin: 5px 0;
  }
}
</style>
