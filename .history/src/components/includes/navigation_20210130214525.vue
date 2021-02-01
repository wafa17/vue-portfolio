<template>
  <div>
    <nav class="navbar navbar-expand-md navbar-dark" style="background-color: #2F3E46; " >
      <div class="container">
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
      </div>
    </nav>
  </div>
</template>

<style lang="css" scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
.navbar-custom {
	background-color: #5f4dee;
	box-shadow: 0 0.0625rem 0.375rem 0 rgba(0, 0, 0, 0.1);
	font: 700 0.875rem/0.875rem "Open Sans", sans-serif;
	transition: all 0.2s;
}

.navbar-custom .container {
	max-width: 87.5rem;
}
.navbar-brand {
  font-family: "Poppins";
  font-weight: 950;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  color: white;
}
.nav-link{
  font-family: "Poppins";
  color: white;
  font-weight:400;
  padding: 30px;
  
}
.navbar.navbar-expand-md .navbar-dark{
  padding-right: 30px;
}
</style>
