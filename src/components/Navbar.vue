<template>
<nav className="nav">
  <div class="container-fluid">
    <div class="nav-mobile">
      <div class="nav-brand">
        <a href="/">WizHubb</a>
      </div>
      <div>
        <button class="nav-menu-button">
          <svg class="nav-menu-hamburger" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>
    </div>
    <div class="nav-menu">
      <div class="nav-left"></div>
      <div class="nav-right">
        <div class="nav-item">WizHubb Alpha is out!</div>
        <div class="nav-item">
          <router-link to="/profile" class="button">User Profile
          </router-link>
        </div>
        <div class="nav-item">
          <router-link to="/signup" class="button button-create">Create Account
          </router-link>
        </div>
      </div>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
.nav {
  width: 100%;
  display: flex;
  justify-content: space-between;
  min-height: 70px;
  align-items: center;
  flex-wrap: wrap;
  background: #ffffff;
  box-shadow: 0px 0px 4px rgba(0, 0, 0, 0.1);
}

.nav-brand {
  height: 70px;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  margin-right: 2rem;
}

.nav-brand>a {
  font-size: 24px;
  text-decoration: none;
  color: #000;
  font-weight: 700;
}

.nav-left,
.nav-right {
  display: block;
}

.nav-menu {
  width: 100%;
  display: block;
  flex-grow: 1;
}

.nav-link,
.nav-item {
  height: 70px;
  display: flex;
  align-items: center;
  padding: 0 0.75rem;
}

.nav-item a {
  text-decoration: none;
}

.nav-mobile {
  width: 100vw;
  height: 70px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 0.625rem;
  border-bottom: 1px solid rgba(238, 238, 238, 0.479);
}

.nav-menu-button {
  display: flex;
  align-items: center;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  padding-left: 0.75rem;
  padding-right: 0.75rem;
  border-radius: 0.25rem;
}

.nav-link,
.nav-item {
  flex-grow: 1;
}

.nav-link {
  color: #777;
  text-decoration: none;
  border-top: 2px solid transparent;
  border-bottom: 2px solid transparent;
}

.nav-svg {
  margin-right: 5px;
  margin-top: 4px;
}

.nav-link:hover .nav-svg svg path {
  stroke: #4673e4;
  transition: stroke ease-in-out 300ms;
}

.nav-link:hover {
  color: #0f67be;
  border-bottom-color: #0f67be;
  transition: all ease-in-out 300ms;
}

.nav-link.active {
  border-bottom-color: #0f67be;
}

.nav-menu-hamburger {
  width: 1rem;
  height: 1rem;
  fill: currentColor;
}

@media (min-width: 1024px) {
  .nav-brand {
    height: 70px;
  }

  .nav>.container-fluid {
    width: 100%;
    display: flex;
    align-items: stretch;
  }

  .nav-left,
  .nav-right {
    display: flex;
    align-items: center;
  }

  .nav-right {
    margin-left: auto;
  }

  .nav-left {
    margin-right: auto;
  }

  .nav-menu {
    width: auto;
    display: flex;
    align-items: center;
  }

  .nav-link,
  .nav-item,
  .nav-brand {
    height: 70px;
    display: flex;
    align-items: center;
  }

  .nav-menu-button {
    display: none;
  }

  .nav-mobile {
    width: auto;
    border-bottom: unset;
  }
}

@media (min-width: 1280px) {
  .nav>.container-fluid {
    width: 100%;
    display: flex;
    align-items: stretch;
  }
}
</style>
