<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="" fixed="top" class="cols">
      <b-navbar-brand href="#">
        <img src="http://tiidelab.com/" />

        <p class="parag">TIIDELAB</p></b-navbar-brand
      >

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-c nollapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <a href="#"> Home </a>
          <a href="#"> Our Programs</a>

          <a href="#"> About us </a>
          <a href="#"> Contact </a>

          <b-nav-item-dropdown text="Lang" right>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown>

          <b-nav-item-dropdown right>
            <!-- Using 'button-content' slot -->
            <template v-slot:button-content>
              <em>User</em>
            </template>
            <b-dropdown-item href="#">Profile</b-dropdown-item>
            <b-dropdown-item href="#">Sign Out</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style>
.cols {
  margin-top: 0px;
  background-color: white;
  color: #ffffff;
}
.parag {
  font-size: 20px;
  font-weight: bold;
  color: #3edeff;
}
</style>
