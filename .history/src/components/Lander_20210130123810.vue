<template>
  <div>
    <!-- lander section -->
    <section class="section">
      <div class="container-fliud">
        <p class="univ">Computer Science Student at Telkom Univeristy</p>
        <h1 class="name">WAFA ZAHIDA</h1>
        <p class="job">
          This is a fun project I built while learning vue.js and bootstrap
        </p>
        <button
          type="button"
          class="btn btn-primary btn-lg"
          data-toggle="modal"
          data-target=".bd-example-modal-lg"
        >
          Contact
        </button>
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
.section {
  padding-top: 10%;
  padding-bottom: 10%;
  background-color: #2f3e46;
  color: white;
}
.protfolio {
  background-color: #34345238;
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

  /* position: static;
  width: 371px;
  height: 9px;
  left: 265px;
  top: 0px; */

  font: "Lato";
  font-style: normal;
  font-weight: 800;
  font-size: 12.2707px;
  line-height: 71.5%;

  /* identical to box height, or 9px */
  text-align: center;

  color: #ffe074;

  /* Inside Auto Layout */
  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 30px 0px;
}
.name {
  /* WAFA ZAHIDA */

  /* position: static;
  width: 901px;
  height: 44px;
  left: 0px;
  top: 39px; */

  font: "Poppins";
  font-style: normal;
  font-weight: 800;
  font-size: 62.797px;
  line-height: 71.5%;

  /* or 45px */
  text-align: center;

  /* Pure White */
  color: #ffffff;

  /* Inside Auto Layout */
  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 30px 0px;
}
.job {
  /* UI/UX and Web Design Enthusiast */

  /* position: static;
  width: 294px;
  height: 13px;
  left: 303.5px;
  top: 113px; */

  font: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 16.6015px;
  line-height: 13px;
  text-align: center;
  letter-spacing: 0.02em;

  /* Pure White */
  color: #ffffff;

  /* Inside Auto Layout */
  flex: none;
  order: 2;
  flex-grow: 0;
  margin: 30px 0px;
}
</style>
