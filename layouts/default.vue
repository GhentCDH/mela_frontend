<template>
  <b-container fluid="lg">
    <header>
      <b-navbar toggleable="lg" type="light" variant="light" class="mb-3">
        <b-navbar-brand to="/"> MELA: The Meaning of Language </b-navbar-brand>

        <!-- BootstrapVue SSR -->
        <ClientOnly>
          <b-navbar-toggle target="nav-collapse" />

          <b-collapse id="nav-collapse" is-nav class="text-primary">
            <b-navbar-nav>
              <b-nav-item to="/texts"> Texts </b-nav-item>
              <b-nav-item to="/words" disabled> Words </b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </ClientOnly>
      </b-navbar>
    </header>
    <main>
      <slot />
    </main>
  </b-container>
</template>
