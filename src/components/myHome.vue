<!-- <template>
<h2>Email: {{ email }}</h2>
<h2>Mobile: {{ mobile}}</h2>
<h2>my Name is : {{getName("alnfi")}}</h2>
<h2>my Name is : {{getPas("Yusuf")}}</h2>
<h2>All Data is : {{getData()}}</h2>
</template>

<script>
    export default {

        name: "myHome",
        data()

        {
            return {
                email: 'alnafi.com',
                mobile: 9999999,
                getName: function (a) {
                    return a;
                }
            }
        },

        methods: {
            getPas() {
                return 'aanafi';

            },

            //     getData()
            //     {
            //         return         
            //            { names:'school'
            //              email:this.email
            //             }

            //    }
        }
    };
</script>

<style>
    h2 {
        color: rgb(58, 3, 196);
    }
</style> -->


<!-- <template>
    <h1 v-on:mousemove="getConsole()">Home components</h1>

    <button v-on:Click="getData('button 1 click')">Click Me</button>
    <button v-on:Click="getData('button 2 click')">Click Me</button>
    <button @click="count++">Count is: {{ count }}</button>
    <h2>{{ count }}</h2>
   <!-- <button @Click="getData('button 1 click')">Click Me</button>
    <button @Click="getData('button 2 click')">Click Me</button>  -->
</template>

<script>
export default {
    name:"myHome",
   data(){
   return{
    count:0,
   }
   },
    methods:{
        getData(){

            this.count = 10;
        // alert(data);
            // alert(data);
            // alert("function button");
        },
        getConsole(){
            console.warn("function called");
         }
    
        }
}
</script>
<style>

</style> 
<!-- <template>
    <h1>alnafiiii</h1>
    <input type="text">
    <h2>{{ count }}</h2>
</template>
<script> 

export default {
 name:"Binding",
    data()
  {
    return{
count:0
    }

  }
};
</script>
<style>

</style>
 --> -->
