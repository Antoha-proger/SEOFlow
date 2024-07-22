<template>
  <ul class="main-menu">
    <li class="menu-item"><a href="#" class="menu-link">Home</a></li>
    <li class="menu-item"><a href="#" class="menu-link">Why SEO?</a></li>
    <li class="menu-item"><a href="#" class="menu-link">Services</a></li>
    <li class="menu-item"><a href="#" class="menu-link">Team</a></li>
    <li class="menu-item"><a href="#" class="menu-link">Pricing</a></li>
    <li class="menu-item"><a href="#" class="menu-link">Blog</a></li>
    <li class="menu-item"><a href="#" class="menu-link">Contact</a></li>
  </ul>
</template>

<style scoped>
.main-menu {
  display: flex;
  column-gap: 30px;
  list-style-type: none;
}

.menu-link {
  text-decoration: none;
  color: var(--menu-list-color);
  transition: color 0.3s;
}

.menu-link:hover {
  color: var(--base-yellow-color);
}
</style>
