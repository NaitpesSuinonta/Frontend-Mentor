<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,100..900;1,9..144,100..900&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
  .card {
    border-radius: 0.5em;
    background-color: hsl(0, 0%, 100%);
    color: hsl(212, 6%, 44%);
    display: flex;
    padding: 1em;
    flex-direction: column;
    box-shadow: 0 0 1em 0 hsl(234, 12%, 34%);
    margin-bottom: 1em;
  }
  p {
    text-align: center;
    margin-top: 0;
  }
  h2 {
    font-weight: 200;
    margin-bottom: 0;
  }
  span {
    font-weight: 600;
  }
  .card h3 {
    font-weight: 600;
  }
  img {
    align-self: flex-end;
    margin: 1em 1em 1em 0;
  }
  .root {
    font-family: Poppins;
    font-size: 15px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 1em;
    row-gap: 1.25em;
  }
  .first {
    border-top: 0.4em hsl(180, 62%, 55%) solid;
  }
  .second {
    border-top: 0.4em hsl(0, 78%, 62%) solid;
  }
  .third {
    border-top: 0.4em hsl(34, 97%, 64%) solid;
  }
  .fourth {
    border-top: 0.4em hsl(212, 86%, 64%) solid;
  }

  @media (min-width: 768px) {
    .container {
      display: grid;
      gap: 1em;
      align-items: center;
      width: 80vw;
    }
    .first {
      grid-row: 1 / 3;
      align-self: center;
    }
    .second {
      grid-row: 2 / 1;
    }
    .third {
      grid-row: 2 / 2;
    }
    .fourth {
      grid-row: 3 / 1;
      align-self: center;
    }
  }
</style>

<template>
    <div class="root">
      <h2>
        Reliable, efficient delivery<br />
        <span>Powered by Technology</span>
      </h2>
      <p>
        Our Artificial Intelligence powered tools use millions of project data points 
        to ensure that your project is successful
      </p>
      <div class="container">
        <div class="card first">
        <h3>Supervisor</h3>
        Monitors activity to identify project roadblocks
        <img src="../../public/four-card-feature-section/icon-supervisor.svg" alt="magnifier"/>
        </div>
        <div class="card second">
          <h3>Team Builder</h3>
          Scans our talent network to create the optimal team for your project
          <img src="../../public/four-card-feature-section/icon-team-builder.svg" alt="home" />
        </div>
        <div class="card third">
          <h3>Karma</h3>
          Regularly evaluates our talent to ensure quality
          <img src="../../public/four-card-feature-section/icon-karma.svg" alt="karma" />
        </div>
        <div class="card fourth">
          <h3>Calculator</h3>
          Uses data from past projects to provide better delivery estimates
          <img src="../../public/four-card-feature-section/icon-calculator.svg" alt="calculator" />
        </div>
      </div>
    </div>
  </template>


  