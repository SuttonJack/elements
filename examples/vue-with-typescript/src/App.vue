<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <div class="left-header">
      <a class="mux-logo" href="https://www.mux.com/player" target="_blank">
        <img width="81" height="26" src="/images/mux-logo@2x.webp" alt="Mux logo" decoding="async" />
      </a>
      <h1><RouterLink to="/">Elements</RouterLink></h1>
    </div>
    <div class="right-header">
      <a class="github-logo" href="https://github.com/muxinc/elements" target="_blank">
        <img width="32" height="32" src="/images/github-logo.svg" alt="Github logo" />
      </a>
    </div>
  </header>

  <RouterView />
</template>

<style>
@import "@/assets/base.css";
</style>
