<template>
<div>
  <b-navbar toggleable="lg" type="dark" variant="dark">
    <b-navbar-brand href="#">Bulbazavr's JavaScript training field</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Some kind of blog</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item-dropdown text="Projects" right>
          <b-dropdown-item href="#">Calculator</b-dropdown-item>
          <b-dropdown-item href="#">Currency converter</b-dropdown-item>
          <b-dropdown-item href="#">To-Do List</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown text="Games" right>
          <b-dropdown-item href="#">Snake</b-dropdown-item>
          <b-dropdown-item href="#">Arcanoid</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<style>
</style>
