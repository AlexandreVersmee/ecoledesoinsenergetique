<template>
    <header>
      <nav class="navbar navbar-expand-md navbar-light bg-light fixed-top mb-4">
        <div class="container">
          <a class="navbar-brand" href="/"><img id="logo" src="../logo.jpg"></a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false"
                  aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse " id="navbarCollapse">
            <ul class="navbar-nav ml-auto">
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="domaines" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                  Nos domaines




                </a>
                <div class="dropdown-menu" aria-labelledby="domaines">
                  <a class="dropdown-item" href="#">Magnétisme</a>
                  <a class="dropdown-item" href="#">Lahochi</a>
                  <a class="dropdown-item" href="#">Réfléxologie Plantaire</a>
                  <a class="dropdown-item" href="#">Aromathérapie</a>
                  <a class="dropdown-item" href="#">Auriculothérapie</a>
              </div>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="formations" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                  Nos formations
                </a>
                <div class="dropdown-menu" aria-labelledby="formations">
                  <a class="dropdown-item" href="#">Soins énergétiques niveau 1</a>
                  <a class="dropdown-item" href="#">Soins énergétique niveau 2</a>
                  <a class="dropdown-item" href="#">Pose de ventouses</a>
                  <a class="dropdown-item" href="#">Réflexologie plantaire niveau 1</a>
                  <a class="dropdown-item" href="#">Réflexologie plantaire niveau 2</a>
                  <a class="dropdown-item" href="#">Auriculothérapie </a>
                  <a class="dropdown-item" href="#">Huiles essentielles niveau 1</a>
                  <a class="dropdown-item" href="#">Huiles essentielles niveau 2</a>
                  <a class="dropdown-item" href="#">Professionnalisation</a>
                </div>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="intervenants" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                  Nos intervenants
                </a>
                <div class="dropdown-menu" aria-labelledby="intervenants">
                  <a class="dropdown-item" href="#">Action</a>
                  <a class="dropdown-item" href="#">Another action</a>
                  <a class="dropdown-item" href="#">Something else here</a>
                </div>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
              </li>

            </ul>
          </div>
        </div>
      </nav>
    </header>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #logo{
    height: 30px;
  }
</style>
