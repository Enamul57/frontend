<template>
  <div id="header">
    <div class="navbarone">
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
    <div class="navbartwo">
      <ul>
        <li><a href="">Stays</a></li>
        <li><a href="">Flights</a></li>
        <li><a href="">Car entals</a></li>
        <li><a href="">Attractions</a></li>
        <li><a href="">Airport Taxis</a></li>
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
.navbarone {
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
  margin-top: 1em;
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
  margin-left: 20%;
}
.navbar li {
  text-align: center;
  padding: 0.5em 0.5em;
  margin-right: 0.2em;
}
.menu a {
  color: white;
  text-align: center;
}
.navbar img {
  border-radius: 50%;
  height: 30px;
}
.question i {
  border-radius: 49%;
  border: 1px solid white;
  padding: 15px;
}
.question a {
  padding-left: 8px;
  padding-right: 8px;
}
.btnBox {
  border: 1px solid white;
  text-align: center;
  margin: 0.5em;
}
.menu .btnPrime {
  font-size: 1rem;
  border: 1px solid white;
  font-weight: bold;
  background: white;
  margin: 0.5em;
}
.btnPrime a {
  color: #003580 !important;
}
.navbartwo{
  width:100%;
  background:#003580;
  height:80vh;
  margin:0 auto;
}
.navbartwo ul{
  display:flex;
  width:50%;
  float:left;
  margin-left:10%;
  list-style:none;
  text-decoration:none;
  
}
.navbartwo li{
  margin:1em;
}
.navbartwo a{
  font-size:1rem;
}










@media screen and (max-width: 760px) {
  .menu a,
  .btnPrime,
  .btnBox {
    font-size: 0.8rem;
  }
  .navbar li {
    padding: 0.3em 0.3em;
    margin-right: 0.2em;
  }
}
@media screen and (min-width: 550px) and (max-width: 650px) {
  .menu a,
  .btnPrime,
  .btnBox {
    font-size: 0.7rem;
  }
  .navbar li {
    padding: 0.1em 0.1em;
    margin-right: 0.2em;
  }
}
@media screen and (min-width: 450px) and (max-width: 549px) {
  .menu a,
  .btnPrime,
  .btnBox {
    font-size: 0.6rem;
  }
  .btnBox a {
    padding: 0.6em;
  }
  .navbar li {
    padding: 0.1em 0.1em;
    margin-right: 0.2em;
  }
  .logo h3 {
    font-size: 1.1rem;
  }
  .navbar ul {
    margin-left: 15%;
  }
}

@media screen and (min-width: 380px) and (max-width: 449px) {
  .logo {
    width: 40%;
  }

  .logo h3 {
    font-size: 1rem;
  }
  .navbar {
    width: 70%;
  }
  .menu a,
  .btnPrime,
  .btnBox {
    font-size: 0.5rem;
  }
  .question {
    padding-left: 5px;
    padding-right: 5px;
  }
  .navbar li {
    padding: 0.1em 0.1em;
    margin-right: 0.2em;
  }
  .navbar ul {
    margin-left: 10%;
  }
}
@media screen and (min-width: 200px) and (max-width: 380px) {
  .logo {
    width: 40%;
  }

  .logo h3 {
    font-size: 0.8rem;
    float: left;
  }
  .navbar {
    width: 70%;
  }
  .menu a,
  .btnPrime,
  .btnBox {
    font-size: 0.3rem;
  }
  .navbar li {
    padding: 1px 1px;
    margin-right: 0.2em;
  }
  .navbar ul {
    margin-left: 5%;
  }
}
</style>
