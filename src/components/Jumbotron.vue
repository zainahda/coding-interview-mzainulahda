<template>
  <div>
    <div>
  <b-jumbotron class="jumbotron">
    <h1>Let'Go <br> to Raja Ampat</h1>
    <p>Temukan keindahan Indonesia bersama kami</p>
    <b-button variant="success" href="#" class="button ">More Info</b-button>
  </b-jumbotron>
</div>
  </div>
</template>

<script>
export default {
  name: 'Jumbotron',
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800&display=swap');

.jumbotron {
  background-image: url(../assets/raja.jpg);
  background-size: cover;
  height: 860px;
}
.jumbotron h1 {
  font-family:'Montserrat', sans-serif;
  color: #fff;
  font-size: 72px;
  font-weight: 800;
  display: flex;
  justify-content: center;
  margin-top: 200px;
  text-shadow: 5px 7px 5px rgba(0, 0, 0, 0.45);
}
.jumbotron p{
  color: #fff;
  font-family:'Montserrat', sans-serif;
  font-size: 25px;
  text-shadow: 5px 7px 5px rgba(0, 0, 0, 0.45);
  display: flex;
  justify-content: center;
}
.button {
  margin-left: 500px;
}


@media (min-width: 375px) {
  .button {
  margin-left: 10px;
}
.jumbotron p{
  display: none;
}
}
</style>