<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <nav>
    <ul>
      <li>
        <RouterLink to="/">Home</RouterLink>
      </li>
      <li>
        <RouterLink to="/about">About</RouterLink>
      </li>
    </ul>
  </nav>
  <div>
    <RouterView />
  </div>
</template>
