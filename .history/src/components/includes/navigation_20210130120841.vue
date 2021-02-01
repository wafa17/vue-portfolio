<template>
  <div>
    <nav class="navbar navbar-expand-lg" style="background-color: #2F3E46; ">
      <a class="navbar-brand" href="#">my portfolio</a>
      <button
        class="navbar-toggler navbar-dark"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link " href="#">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<style lang="css" scoped>
.navbar-brand {
  font-display: "Poppins";
  font-weight: 950;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 10px;
  color: white;
}
.nav-link{
  color: white;
  font-weight:400;
  font-display: "Poppins";
}
.navbar-toggler > .navbar-dark{
    border-block-end-width: medium;
}
</style>
