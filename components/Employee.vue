<template>
    <div id="employee">
        <h4>employee</h4>
        <h6 v-for='jokes in joke' :key='jokes'>{{jokes.address}}</h6>
    </div>
</template>
<script>
import axios from 'axios';
export default {
    name:'Employee',
    data(){
        return {
            joke:[],
        }
    },
   async created(){
       const config  = {
           headers:{
               'Accept':'application/json',
           }
       }
        const res = await axios.get('http://127.0.0.1:8000/api/employee');  
        this.joke = res.data;
        console.log(this.joke);
    }
}
</script>