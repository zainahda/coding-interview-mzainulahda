<template>
  <div>
  <b-navbar toggleable="lg" type="dark" variant="primary">
    <b-navbar-brand href="#">Indonesia</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class=" ml-auto" >
        <b-nav-item href="#">Home</b-nav-item>
        <b-nav-item href="#">What to See</b-nav-item>
        <b-nav-item href="#">What to Do</b-nav-item>
        <b-nav-item href="#">Packages</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="btn-search my-2 my-sm-0" variant="success" type="submit">Search</b-button>
        </b-nav-form>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
