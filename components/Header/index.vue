<template>
  <div id="header">
    <div class="logo">
      <h3>Booking.com</h3>
    </div>
    <div class="navbar">
      <ul class="menu">
        <li><a href="">BDT</a></li>
        <li>
          <a href=""><img src="~/assets/img/Usa.png" alt="" /></a>
        </li>
        <li class="question">
          <a href=""><i class="fas fa-question"></i></a>
        </li>
        <li class="btnBox"><a href="">List Your Property</a></li>
        <li class="btnPrime"><a href="">Register</a></li>
        <li class="btnPrime"><a href="">Sign In</a></li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: "Header",
  head() {
    return {
      title: "Booking.com",
      meta: [
        {
          hid: "booking.com",
          name: "booking.com",
          content: "",
        },
      ],
    };
  },
};
</script>
<style>
#header {
  width: 100%;
  display: flex;
  font-family: Avenir Next, BlinkMacSystemFont, -apple-system, Segoe UI, Roboto,
    Helvetica, Arial, sans-serif;
  background: #003580;
  justify-content: space-between;
}
.logo {
  width: 30%;
  text-align: center;
}
.logo h3 {
  font-size: 1.5rem;
}
.navbar {
  width: 60%;
  margin: 0 auto;
  display: flex;
}
.navbar ul {
  display: flex;
  width: 100%;
  text-decoration: none;
  list-style: none;
}
.navbar li {
  text-align: center;
  padding: 0.5em 0.5em;
}
.menu a{
  color: white;
}
.navbar img {
  border-radius: 50%;
  height: 30px;
}
.question {
  border-radius: 49%;
  border: 1px solid white;
  padding-left: 15px;
  padding-right: 15px;
  padding-top: 12px;
  padding-bottom: 12px;
}
.btnBox {
  border: 1px solid white;
}
.menu .btnPrime {
  font-size: 1rem;
  border: 1px solid white;
  font-weight: bold;
  background: white;
}
.btnPrime a{
  color: #003580 !important;

}
</style>
