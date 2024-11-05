<template>
  <div
    class="container-fluid p-5 min-vh-100 d-flex align-items-center justify-content-center"
  >
    <br /><br />
    <div class="text container my-5">
      <div class="row align-items-center my-5">
        <div class="col-md-5 col-12 text-center text-md-left mb-md-0">
          <hr />
          <h4>Digital Collection</h4>
          <h2>Essay</h2>
          <h4>Reflection of this website</h4>
        </div>
        <div class="col-md-7 col-12 p-5 my -4">
          <h4 class="text-center text-md-left p-5 my-4">Embedded Essay</h4>
          <div class="card-body text-center text-md-left">
            <h6 class="card-title"><strong>Final Assignment: DC</strong></h6>
            <h6 class="card-text">A brief summary of the digital collection.</h6>
            <iframe
              src=""
              frameborder="0"
              width="100%"
              height="300px"
              class="my-3"
            ></iframe>
            <a href="" download="" class="btn btn-success mt-3">Download</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
*,
*::after,
*::before {
  box-sizing: border-box;
  scroll-behavior: smooth;
}

html {
  font-family: "Rajdhani", sans-serif;
}

body {
  background: linear-gradient(95deg, #cacae7, #f6fff8 60%, #cacae7);
  background-size: cover;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}

/* Responsive Container */
.container-fluid {
  max-width: 1200px;
}

/* Text Container Styling */
.text-container {
  animation: fade 2s ease-in;
}

h2,
h4 {
  color: #0a342b;
  font-weight: 500;
  text-align: center;
  text-shadow: 1px 1px 1px #000, 3px 3px 5px rgb(224, 138, 18);
}

h2 {
  font-size: 2.5em;
  margin-top: 20px;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}

h4 {
  font-size: 1.2em;
  margin-top: 20px;
}

.card-body {
  padding: 1rem;
}

/* Button Styles */
.btn-success {
  padding: 0.5rem 1.5rem;
  font-size: 1rem;
  transition: background-color 0.3s;
}
.btn-success:hover {
  background-color: #28a745;
}

/* Keyframe Animations */
@keyframes fade-in {
  from {
    opacity: 0;
    transform: scale(0) translateX(200%);
  }
  to {
    opacity: 1;
    transform: scale(1) translateX(0);
  }
}

/* Responsive Adjustments */
@media (max-width: 992px) {
  h2 {
    font-size: 2em;
  }
  h4 {
    font-size: 1.1em;
  }
}

@media (max-width: 768px) {
  h2 {
    font-size: 1.8em;
  }
  h4 {
    font-size: 1em;
  }

  .text-container {
    padding: 2rem 1rem;
  }

  /* Ensure columns stack */
  .row {
    flex-direction: column;
  }

  /* Adjust button size and alignment */
  .btn-success {
    width: 100%;
    padding: 0.7rem;
    font-size: 0.9rem;
  }
}

@media (max-width: 576px) {
  .container-fluid {
    padding: 1rem;
  }

  h2 {
    font-size: 1.5em;
  }

  h4 {
    font-size: 0.9em;
  }

  .btn-success {
    width: 100%;
    padding: 0.8rem;
  }
}
</style>
