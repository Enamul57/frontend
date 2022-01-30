<template>
    <div class="header_nav">
      <div class="logo">
        <h2>Booking.com</h2>
      </div>
      <div class="menu">
        <ul class='menu_ul'>
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
        { charset: 'utf-8' },
        { name: 'viewport', content: 'width=device-width, initial-scale=1' },
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
*{
	margin:0;
	padding:0;
	box-sizing:border-box;
}

body{
	font-size:1.125rem;
}
h1{
	font-size:3rem;
}
h1,h2,h3,h4,h5,h5{
	margin:0;
}
a {
      all: unset;
 }
 a:hover{
	 cursor:pointer;
 }

.header_nav {
  display: flex;
  background: #003580;
  height: 60vh;
  margin:0 auto;
  width:100%;
}
.logo{
  text-align: center;
  width:100%;
  margin:1em auto;

}

.menu{
  width:100%;
  margin:0.5em auto;
}
.menu ul{
  display:flex;
  list-style:none;
  text-decoration:none;
}
.menu li{
  padding:0.5em ;
  margin:0.1em;
}
.menu li a{
  padding: 0.2em;
}
.menu_ul img{
 border-radius: 50%;
  height: 30px;
}
li a i{
 

  border:1px solid white;
  padding:0.7em;
  border-radius:50%;
}
.btnBox{
    border: 1px solid white;
    font-weight:bold;
}
.menu .btnPrime {
  font-size: 1rem;
  border: 1px solid white;
  font-weight: bold;
  background: white;
}
.btnPrime a{
  color:#003580;
}

@media screen and (max-width:600px) {
  .header_nav{
    display:block;
    width:100%;
  }
  .menu li a{
    font-size:0.7rem;
  }
}

@media screen and (max-width:430px) {
  .menu li a{
    font-size:0.7rem;
  }
}
@media screen and (min-width:288px) and (max-width:366px){
  .menu li{
    padding:0.4em;
  }
}

</style>