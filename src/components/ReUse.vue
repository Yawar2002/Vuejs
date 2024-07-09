<!-- <template>
    <div class="User">  
        <h2>{{ data.name }}</h2>
        <h2>{{ data.email }}</h2>
        <h3>{{ text }}</h3>
        <ul>
        <li v-for="item in ReUse" :key="item.name">
            {{ item.name }}
             <br>
            {{ item.email }}
            <button v-on:click="getData(name)">Alert Name</button>
        </li>
    </ul>
   </div>
</template>
<script>
export default {
    name: "ReUse",
    props: {
        data:Object,
    },
    data() {
            return {
                ReUse: [{
                        name: 'Ali',
                        email: 'ali@gmail.com'
                    },
                    {
                        name: 'Ali',
                        email: 'ali@gmail.com'
                    },
                    {
                        name: 'Ali',
                        email: 'ali@gmail.com'
                    }
                ]
            }
        },

    // datas(){
    //     return{
    //         text:"Karachi@gmail.com",
    //     }
    // },
    methods: {
        getData(name){
            alert(name);
        }
    }
}
</script>
<style >
.User{
    background-color: rgb(21, 21, 155);
    padding: 10px;
    margin-bottom: 20px;

}
</style> -->