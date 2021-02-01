<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <button class="navbar-toggler" type="button" data-toggle="collapse" 
              data-target="#navbarTogglerDemo03" 
              aria-controls="navbarTogglerDemo03" 
              aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand" href="#">my portfolio</a>
            <div class="collapse navbar-collapse" id="navbarTogglerDemo03" >
                <ul class="navbar-nav ml-auto mt-2 mt-lg-0 ">
                <li class="nav-item active">
                    <a class="nav-link" href="#">
                      Home 
                    <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Portfolio</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact</a>
                </li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<style lang="css" scoped>
    .navbar-brand {
       font-display: "Poppins";
       display: flex;
       flex-direction: row;
       justify-content: center;
       align-items: center;
       padding: 10px; 
    }
</style>