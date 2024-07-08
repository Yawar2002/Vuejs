<!-- <template>
<h2>Check Box</h2>

<input type="checkbox" value="Java" v-model="Technology" id="Java">
<lebel for="Java"> Node</lebel>
<br />
<input type="checkbox" value="Node" v-model="Technology" id="Node">
<lebel for="Node"> Node </lebel>
<br />
<input type="checkbox" value="Nuxt" v-model="Technology" id="Nuxt">
<lebel for="Nuxt"> Nuxt </lebel>
<h3>U-Technology:{{ Technology }}</h3>
<br />
<h4>Who am I</h4>
<input type="radio" value="Student" v-model="who" id="Student">
<lebel for="Student"> Student </lebel>
<br/>
<input type="radio" value="Developer" v-model="who" id="Developer">
<lebel for="Developer"> Developer </lebel>
<br>
<h3>I am a :{{ who }}</h3>
</template>

<script>
export default {
    Namess: "checkbox",
    props: {
        msg: String
    },
    data() {
        return {
            Technology: [],
            who: null

        }

    }
}
</script>

<style>

</style> -->
<!-- //=================If Else Conditions=========================
//================================================================ -->
<!-- <template>
<h2 v-if="show">If Condition</h2> 
<h2 v-else> Else Condition</h2>    
<button v-on:click="show=!show">toogle</button>
</template>
<script>
export default {
    
    Namess: "checkbox",
    props: {
        msg: String
    },
    data() {
        return {
            show: true
            

        }
}
}
</script>
<style>

</style>-->
  
  
 <!-- //=================Loops=========================
 <template>
    <h1>For Loop</h1>
        <ul>
            <li v-for="item in tech" :key="item">
                {{ item}}
            </li>
        </ul>
<br>
<br> 
        <ul>
            <li v-for="item in user" :key="item">
               Name is: {{ item.name}} 
               <br>
               Email is: {{ item.email}}
            </li>
        </ul>
</template>
  <script>
  export default {
    data(){
        return{
            tech:['Java','Node','Nuxt','Html','Css'],
            user:[
                {
                    name:"yawar", 
                    email:'yawar@gmail.com'
                },
                {
                    name:"Ali", 
                    email:'Ali@gmail.com'
                },
                {
                    name:"yasir", 
                    email:'yasir@gmail.com'
                }
            ]
        }
    }
  }
  </script>
  <style>
</style> -->

<!-- //Pass Data Parent to Child Component -->
