<template>
  <div>
    <b-navbar
      toggleable="lg"
      type="dark"
      variant="info"
      fixed="top"
      class="columns"
    >
      <b-navbar-brand href="#">
        <p class="company">
          Get your favorite meals delivered to you. Stay safe, Order in.
        </p>
        <p></p
      ></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-c nollapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form size="sm" class="mr-sm-2"></b-form>
            <b-button size="sm" class="my-2 my-sm-0" type="submit"
              >Order Now</b-button
            >
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<style>
.columns {
  background-color: red;
  margin-top: 50px;
}
</style>
