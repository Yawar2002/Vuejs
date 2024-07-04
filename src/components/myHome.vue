<template>
    <h2>Email: {{ email }}</h2>
    <h2>Mobile: {{ mobile}}</h2>
    <h2>my Name is : {{getName("alnfi")}}</h2>
    <h2>my Name is : {{getPas("Yusuf")}}</h2>
    <!-- <h2>All Data is : {{getData()}}</h2> -->
</template>
<script>
export default {
   
    name:"myHome",
     data() 
        
        {
           return {
                email: 'alnafi.com',
                mobile:9999999,
                getName : function(a)
                {
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
<style scope>
h2{
    color: rgb(58, 3, 196);
}
    
</style>
