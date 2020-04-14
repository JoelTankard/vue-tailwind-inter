<template>
  <div id="app" class="text-inter">
    <div id="nav" class="absolute p-4">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>
