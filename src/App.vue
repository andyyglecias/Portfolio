<template>
  <div id="app">
    <header class="header">
      <div
        class="container-fluid-limited d-flex align-items-center justify-content-between"
      >
        <a href="index.html" class="header-brand"> </a>
        <button class="sections-nav-toggler" aria-label="Toggle navigation">
          <span class="sections-nav-toggler-bar"></span>
          <span class="sections-nav-toggler-bar"></span>
          <span class="sections-nav-toggler-bar"></span>
          <span class="sections-nav-toggler-bar"></span>
        </button>
      </div>
    </header>
    <router-view />
  </div>
</template>

<style></style>
