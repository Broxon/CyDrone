<script>
  let mobile;
  const toggleNav = () => {
    mobile = !mobile;
  };
</script>

<nav class="navbar is-spaced is-transparent" id="Navbar">
  <div class="container">
    <div class="navbar-brand">
      <a href="#Úvod" class="navbar-item">
        <img class="cydrone" src="./assets/img/logo/CyDrone.png" alt="#/" />
      </a>
      <a href="#Úvod" class="navbar-item is-size-5 has-text-black"> CyDrone </a>
      <a class="navbar-burger" class:is-active={mobile} on:click={toggleNav} href="#/">
        <span aria-hidden="true" />
        <span aria-hidden="true" />
        <span aria-hidden="true" />
      </a>
    </div>
    <div class="navbar-menu" class:is-active={mobile}>
      <div class="navbar-end">
        <div class="navbar-start">
          <a class="navbar-item has-text-black" href="#O_nás"> O nás </a>
          <a class="navbar-item has-text-black" href="#Partneři"> Partneři </a>
          <a class="navbar-item has-text-black" href="#Naše_řešení"> Naše řešení </a>
          <a class="navbar-item has-text-black" href="#Kontakt"> Kontakt</a>
        </div>
      </div>
    </div>
  </div>
</nav>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@1,700&display=swap");
  a {
    font-family: "Roboto Mono", monospace;
    font-weight: bold;
  }
</style>
