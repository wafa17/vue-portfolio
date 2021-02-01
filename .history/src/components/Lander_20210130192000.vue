<template>
  <div>
    <!-- lander section -->
    <section class="section">
      <div class="container-fliud">
        <p class="univ">
          Computer Science Final Year Student at Telkom Univeristy
        </p>
        <h1 class="name">WAFA ZAHIDA</h1>
        <p class="job">
          UI/UX Design and Web Design Enthusiast
        </p>
        <button class="button">
          Let's Talk
        </button>
      </div>
    </section>
    <svg
      width="100%"
      height="100%"
      viewBox="0 0 1440 57"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path d="M1440 0H0V57C720 0 1440 57 1440 57V0Z" fill="#2F3E46" />
    </svg>
    <section class="about">
      <div id="aboutme" class="basic-1">
        <div class="container">
          <div class="row col-lg-6">
            <p id="about">About Me</p>
            <div class="text-container">
              <h2>Humble, Creative and a Good Problem Solver</h2>
              <p>
                Hi! I am Wafa. Computer Science final year student. Passionate
                about UI/UX Design and Web Developer. Defined as adaptable,
                insightful, introspective, and interest in exploring complex
                issues. Good at communication and problem solving and also good
                at teamwork. Experienced in UI/UX design, prototyping, and
                wireframing.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- portfolio section -->
    <section class="protfolio">
      <h1>Portfolio</h1>
      <p>These are suppose to be sample projects</p>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <div class="card">
              <div class="card-head">
                <img
                  alt="Vue logo"
                  class="rounded-circle img-custome"
                  src="https://www.wetechnology.cz/wp-content/uploads/2017/02/uxui.jpg"
                />
                <h2>web project</h2>
              </div>
              <hr />
              <div class="card-body">
                <p>
                  Donec sed odio dui. Etiam porta sem malesuada magna mollis
                  euismod. Nullam id dolor id nibh ultricies vehicula ut id
                  elit. Morbi leo risus, porta ac consectetur ac, vestibulum at
                  eros. Praesent commodo cursus magna.
                </p>
                <button type="button" class="btn btn-outline-secondary">
                  More
                </button>
              </div>
            </div>
            <br />
          </div>

          <div class="col-md-4">
            <div class="card">
              <div class="card-head">
                <img
                  alt="Vue logo"
                  class="rounded-circle img-custome"
                  src="https://i.pinimg.com/originals/4a/70/56/4a70563234301578c158dc142384a1c3.png"
                />
                <h2>web project</h2>
              </div>
              <hr />
              <div class="card-body">
                <p>
                  Donec sed odio dui. Etiam porta sem malesuada magna mollis
                  euismod. Nullam id dolor id nibh ultricies vehicula ut id
                  elit. Morbi leo risus, porta ac consectetur ac, vestibulum at
                  eros. Praesent commodo cursus magna.
                </p>
                <button type="button" class="btn btn-outline-secondary">
                  More
                </button>
              </div>
            </div>
            <br />
          </div>

          <div class="col-md-4">
            <div class="card">
              <div class="card-head">
                <img
                  alt="Vue logo"
                  class="rounded-circle img-custome"
                  src="https://cdn.mos.cms.futurecdn.net/wH5y2PkWhCxqKBje8rBp5e.jpg"
                />
                <h2>web project</h2>
              </div>
              <hr />
              <div class="card-body">
                <p>
                  Donec sed odio dui. Etiam porta sem malesuada magna mollis
                  euismod. Nullam id dolor id nibh ultricies vehicula ut id
                  elit. Morbi leo risus, porta ac consectetur ac, vestibulum at
                  eros. Praesent commodo cursus magna.
                </p>
                <button type="button" class="btn btn-outline-secondary">
                  More
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- modal for contact -->

    <section class="">
      <div
        class="modal fade bd-example-modal-lg"
        tabindex="-1"
        role="dialog"
        aria-labelledby="myLargeModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog modal-lg">
          <div class="modal-content">
            <talk />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import talk from "./Contact.vue";
export default {
  name: "Lander",
  components: {
    talk,
  },
};
</script>

<style lang="css" scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap");

.section {
  padding-top: 3%;
  padding-bottom: 5%;
  background-color: #2f3e46;
  color: white;
  font-family: "Poppins";
}
.about{
    text-align: left;
    padding-top: 5%;
    padding-bottom: 5%;
}
#about{
    color:#FFAE00;
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    padding-bottom 10px; ;
}
.protfolio {
  background-color: white;
  padding-top: 8%;
  padding-bottom: 15%;
  /* padding:15% */
}
.img-custome {
  width: 140px;
  height: 140px;
  margin-top: 15px;
}
.univ {
  /* Computer Science Final Year Student at Telkom University */
  font-style: normal;
  font-weight: 800;
  font-size: 14px;
  line-height: 71.5%;

  /* identical to box height, or 9px */
  text-align: center;

  color: #ffe074;

  /* Inside Auto Layout */
  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 40px 0px;
}
.name {
  /* WAFA ZAHIDA */
  font-style: normal;
  font-weight: 800;
  font-size: 84px;
  line-height: 71.5%;

  /* or 45px */
  text-align: center;

  /* Pure White */
  color: #ffffff;

  /* Inside Auto Layout */
  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 40px 0px;
}
.job {
  /* UI/UX and Web Design Enthusiast */
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 13px;
  text-align: center;
  letter-spacing: 0.02em;

  /* Pure White */
  color: #ffffff;

  /* Inside Auto Layout */
  flex: none;
  order: 2;
  flex-grow: 0;
  margin: 40px 0px;
}
.button {
  border: none;
  padding: 10px 40px;
  border-radius: 45px;
  color: white;
  text-align: center;
  font-size: 18px;
  font-weight: 500;
  cursor: pointer;
  background-color: #ef5734;
  background-image: linear-gradient(315deg, #ef5734 0%, #ffcc2f 74%);
  margin: 20px 0px 0px 0px;
  box-shadow: 0px 4px 15px rgba(241, 219, 158, 0.493);
}
</style>
