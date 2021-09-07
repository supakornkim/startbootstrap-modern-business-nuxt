<template>
  <div>
    <body class="d-flex flex-column h-100">
      <main class="flex-shrink-0">
        <b-navbar toggleable="lg" type="dark" variant="dark">
            <b-container class="px-5" >
                <b-navbar-brand to="/">Start Bootstrap</b-navbar-brand>
                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
                <b-collapse id="nav-collapse" is-nav>
                  <b-navbar-nav class="ml-auto">
                    <b-nav-item to="/">Home</b-nav-item>
                    <b-nav-item to="/about">About</b-nav-item>
                    <b-nav-item to="/contact">Contact</b-nav-item>
                    <b-nav-item to="/pricing">Pricing</b-nav-item>
                    <b-nav-item to="/faq">FAQ</b-nav-item>
                    <b-nav-item-dropdown text="Blog">
                      <b-dropdown-item href="#">Blog Home</b-dropdown-item>
                      <b-dropdown-item href="#">Blog Post</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item-dropdown text="Portfolio">
                      <b-dropdown-item href="#">Portfolio Overview</b-dropdown-item>
                      <b-dropdown-item href="#">Portfolio Item</b-dropdown-item>
                    </b-nav-item-dropdown>
                  </b-navbar-nav>
                </b-collapse>
            </b-container>
        </b-navbar>
        <Nuxt />
      </main>
      <footer class="bg-dark py-4 mt-auto">
          <div class="container px-5">
              <div class="row align-items-center justify-content-between flex-column flex-sm-row">
                  <div class="col-auto"><div class="small m-0 text-white">Copyright &copy; Your Website 2021</div></div>
                  <div class="col-auto">
                      <a class="link-light small" href="#!">Privacy</a>
                      <span class="text-white mx-1">&middot;</span>
                      <a class="link-light small" href="#!">Terms</a>
                      <span class="text-white mx-1">&middot;</span>
                      <a class="link-light small" href="#!">Contact</a>
                  </div>
              </div>
          </div>
      </footer>
    </body>
  </div>

</template>
