
<template>
  <div :class="{ 'nav-open': NavbarStore.showNavbar }">
    <router-view name="header" />
    <div>
      <router-view />
    </div>
    <router-view name="footer" />
  </div>
</template>
