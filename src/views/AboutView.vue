<template>
  <div
    id="about"
    class="p-5 my-5 container text-start h-100 justify-content-between shadow-sm"
  >
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
        <div
          class="col-md-6 col-12 myself con shadow-sm rounded-pill"
          data-aos="zoom-in-up"
          data-aos-easing="ease-in"
        >
        <hr>
        <p class="text-black myself soft shadow-sm border border-4">
           
        </p>
       
        <br>
        <br>

        <p class="text-black myself soft shadow-sm border border-4">
           
        </p>
          <p class="text-black myself soft shadow-sm border border-4">
            Welcome to the African Heritage Digital Collection – a unique
            digital space dedicated to preserving and celebrating the rich,
            multifaceted history of Africa's cultural and economic relationships
            with livestock. Our mission is to create a collection that shines a
            light on the historical and modern roles of animals like horses,
            cattle, goats, and sheep in African societies, challenging Western
            narratives that often overlook their significance.
          </p>
         <hr>
          <div class="row text-center m-auto">
            <div class="col">
              <button class="btn"><a href="https://www.britannica.com/animal/horse" target="_blank">Horse</a></button>
              <button class="btn"><a href="https://en.wikipedia.org/wiki/Cattle" target="_blank">Catle</a> </button>
              <button class="btn"><a href="https://www.four-paws.org/campaigns-topics/animals/goat" target="_blank">Goat</a></button>
              <button class="btn"><a href="https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Sheep" target="_blank">Sheep</a></button>
              <button class="btn"><a href="https://www.mediamusicnow.co.uk/royalty-free-sound-effects/animals/goat-sounds" target="_blank">Goat-Sound</a></button>
              <button class="btn"><a href="https://www.youtube.com/watch?v=WHi3EVwBqR4" target="_blank">Catle-Sound</a></button>
            </div>
          </div>
        </div>
        <div>
          <p
            class="text-black myself soft shadow-sm text-align-justify border border-4"
          >
          <h6 class="text-black text-bold text-center">Our vision</h6>
            Our vision is to create a space where African heritage can thrive in
            the digital age. As we grow, we will continue adding items and
            collaborating with communities and researchers to expand our
            collection, bringing even more African voices and perspectives into
            the global conversation.
          </p>
          
          <p
            class="text-black myself soft shadow-sm text-align-justify border border-4"
          >
          <h6 class="text-black text-bold text-center">Our Mission</h6>
            At African Heritage Digital Collection, we believe that Africa’s
            stories deserve to be told in a way that honors their depth,
            diversity, and authenticity. By documenting and curating traditional
            and modern uses of livestock, we aim to provide a valuable resource
            for educators, students, and anyone interested in the continent’s
            cultural heritage. We prioritize African perspectives to help build
            a balanced understanding of history, challenging colonial and
            globalization-driven interpretations that have, for too long, shaped
            global views.
          </p>
         
          <p
            class="text-black myself soft shadow-sm text-align-justify border border-4"
          >
          <h6 class="text-black text-bold text-center">What We Offer</h6>
           Our digital collection brings together various types
          of media to create an engaging, immersive experience. Through
          photos, videos, artifacts, and born-digital creations, we aim to
          give visitors a meaningful journey through time. Each piece in our
          collection is carefully selected, digitized, and presented with
          detailed metadata to ensure accessibility, context, and an enduring
          online presence.
          </p>
          <p
            class="text-black myself soft shadow-sm text-align-justify border border-4"
          >
          <h6 class="text-black text-bold text-center">Ethics and Preservation</h6>
          We are committed to
          ethical practices in digital curation. Each object in our collection
          is displayed with respect for its cultural significance and
          intellectual property rights. We employ standardized metadata
          practices using Dublin Core to enhance accessibility and long-term
          preservation, ensuring that this knowledge is available to future
          generations.
          </p>
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
  background: linear-gradient(
    95deg,
    #d49828,
    hsla(34, 78%, 49%, 0.773),
    hsla(41, 83%, 46%, 0.305),
    #d0b966
  );
  height: auto;
  padding: 20px;
  margin: auto;
}

.std {
  padding: 5px;
  text-align: justify;
  font-size: 1em;
  font-family: "Gill Sans", "Gill Sans MT";
  color: #000;
  font-weight: 500;
  background: linear-gradient(
    95deg,
    #d0b966,
    hsla(34, 78%, 49%, 0.773),
    hsla(41, 83%, 46%, 0.305),
    #d0b966
  );
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
