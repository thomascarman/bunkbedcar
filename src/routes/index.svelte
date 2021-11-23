<main>
  <h1>BunkBedCar.com</h1>
  <p>
    Welcome to our future website featuring our BunkBedCar (coined by our
    daughter Penelope, age 6). She is a 1977 GMC Eleganza II based here in Las
    Vegas, NV.
  </p>

  <img src="/SolarPrep.jpg" alt="Prep for Solar Install" />
</main>

<style lang="scss">
  :global(body) {
    padding: 0;
    margin: 0;
  }

  :global(*) {
    box-sizing: border-box;
  }

  main {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: clamp(720px, 100vw, 980px);
    margin: 0 auto;
    padding: 0;
  }

  p {
    max-width: 70ch;
  }

  img {
    width: 100%;
    max-width: 70ch;
  }
</style>
