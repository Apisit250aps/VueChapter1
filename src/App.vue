<script setup>
import { RouterLink, RouterView } from "vue-router"
import SideMenu from "./components/navigates/SideMenu.vue"
import NavbarMenu from "./components/navigates/NavbarMenu.vue"
</script>

<template>
  <div class="layout-wrapper layout-content-navbar">
    <div class="layout-container">
      <SideMenu />
      <div class="layout-page">
        <NavbarMenu />
        <div class="content-wrapper">
          <div class="container-xxl flex-grow-1 container-p-y">
            <RouterView />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped></style>
