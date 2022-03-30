<template>
  <div>
    <b-navbar
      toggleable="lg"
      type="light"
      class="navbar navbar-expand-lg navbar-dark"
      style="background-color: #172531"
      sticky="true"
    >
      <b-navbar-brand href="#">WECARE4YOU</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/">Home</b-nav-item>
          <b-nav-item href="/patients">Patients</b-nav-item>
          <b-nav-item href="/doctors">Doctors</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style>
.nav-item-log-out {
  margin-left: 750px;
}
</style>
