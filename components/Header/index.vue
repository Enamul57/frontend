<template>
    <div id="header">
       <div class="row topbar">
               <div class='col-md-6 leftbar'>
                    <h2>Booking.com</h2>
               </div>
               <div class="col-md-6 rightbar">
                   <ul class='menu'>
                       <li><a href="">BDT</a></li>
                       <li><a href=""><img src="~/assets/img/Usa.png" alt=""></a></li>
                       <li class='question'><a href=""><i class="fas fa-question"></i></a></li>
                       <li><a href="" class='btnBox' >List Your Property</a></li>
                       <li><a href="" class='btnprime'>Register</a></li>
                       <li><a href="" class='btnprime'>Sign In</a></li>
                   </ul>
               </div>
               
             

           
       </div>
    </div>
</template>
<script>
export default {
    name:'Header',
    head(){
        return{
            title:'Booking.com',
            meta:[
                {
                    hid:'booking.com',
                    name:'booking.com',
                    content:'',
                }
            ]
        }
    }
}
</script>
<style>

#header{
    font-family:Avenir Next,BlinkMacSystemFont,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;
    background:#003580;
    color:white;
    width:100%;
    height:10em;
}
#header h2{
    font-size:1.5rem;
}
.topbar{
    width:100%;
    display:flex;
   position:absolute;
   margin-top:0.4em;
}
.leftbar{
    left:7%;
    top:1.2em;
        position:relative;

}
.rightbar{
    align-items: center;
}
.rightbar ul{
    display:flex;
    list-style: none;
    padding:0 ;
    margin:0;
    width:100%;
    align-items:center;
}
.rightbar li{
    text-decoration: none;
    padding:10px;
    text-align: center;
    margin:0 auto;
    display:inline-block;
    height:40px;
}
.menu a{
    font-size:1rem;
    color:white;
}
.rightbar a:hover{
    color:white;
    text-decoration: none;
    background: #1f4e8f;
   
}
.rightbar img{
    border-radius:50%;
    height:30px;
}
.question a{
    border-radius: 49%;
    border: 1px solid white;
    padding-left: 15px;
    padding-right: 15px;
    padding-top: 12px;
    padding-bottom: 12px;
}
.btnBox{
    font-size:0.7rem;
    color:white;
    background: transparent;
    padding:5px 10px 15px 10px;
    outline:none;
    border:1px solid white;
    text-align: center;
}
 .menu.btnprime{
    font-size:1rem;
    color:#003580;
    background: white;
    padding:5px 10px 15px 10px;
    outline:none;
    border:1px solid white;
    font-weight:bold;
}




@media screen and (min-width:221px)and (max-width:400px) {
    #header h2{
        font-size:0.6rem;
    }
    
    .rightbar a{
        font-size:0.6rem;
        padding:0.1em;
        font-weight:bold;
    }
    .rightbar li{
        padding:0.4em;
    }
    .rightbar img{
    border-radius:50%;
    height:20px;
}
 
}
@media screen and (max-width:220px) {
    #header h2{
        font-size:10px;
    }
    .rightbar a{
        font-size:0.4rem;
    }
        .rightbar li{
        padding:0.2em;
    }
    .rightbar img{
    border-radius:50%;
    height:12px;
}

}
@media screen and (min-width:401px)and (max-width:650px) {
    #header h2{
        font-size:0.7rem;
    }
    
    .rightbar a{
        font-size:0.7rem;
        padding:0.2em;
       
        font-weight:bold;
    }
    .rightbar li{
        padding:0.5em;
    }
    .rightbar img{
    border-radius:50%;
    height:25px;
}
}

</style>
