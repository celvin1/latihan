<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'

</script>

<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="" alt="Flowbite logo" image-url="https://www.templateupdates.com/sites/default/files/2023-01/Hotel%20Logo%20Designs.jpg"></NavbarLogo>        <Carousel :slide="true" :slide-interval="1000"></Carousel>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">Services</NavbarLink>
          <NavbarLink link="#">Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
    
</template>