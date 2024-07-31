<!-- <template>
<ul>
    <li v-for="item in error" v-bind:key="item">
        {{ item }} not valid
    </li>
</ul>
<form id="nafi">
    <h2>Simple Form</h2>
    <label> Email : </label>
    <input type="text" placeholder="Enter Email" v-model="form.Email">
    <br>
    <label> Password : </label>
    <input type="password" placeholder="Enter Password" v-model="form.password">
    <br>

    <select v-model="form.country">
        <option>Pak</option>
        <option>USA</option>
        <option>UK</option>
    </select>

    <h3>Technology</h3>
    <label> Java : </label>
    <input type="checkbox" value="java" v-model="form.technology">
    <br>
    <label> react : </label>
    <input type="checkbox" value="react" v-model="form.technology">
    <br>

    <h4>gender</h4>
    <label> male : </label>
    <input type="radio" value="male" name="gender" v-model="form.gender">
    <br>
    <label> female : </label>
    <input type="radio" value="female" name="gender" v-model="form.gender">

    <br>
    <br>

    <button type="button" @click="login">login</button>
</form>
<br>
</template>

<script>
    export default {
        data() {
            return {
                form: {
                    Email: "",
                    password: "",
                    country: "",
                    technology: [],
                    gender: []
                },
                error: [],
            }
        },
        methods: {
            login() {
                this.error = [];
                for (const item in this.form) {
                    if (this.form[item] === "" || this.form[item].length === 0) {
                        this.error.push(item);
                    }
                }

                if (this.error.length === 0) {
                    alert("data has been submitted");

                }

                console.warn("Login data", this.form.error);
            }
        }

    }
</script>

<style>

</style> -->

<!-- /////////////Form Midifier/////////////////////// -->

<!-- <template>
    <h2>Form MOdifier</h2>
    <input type="text" v-model.number.trim="data">
    <h3>Data is:{{ data }}</h3>
    <h3>Data is:{{ typeof(data) }}</h3>
</template>

<script>
export default {
    data(){
        return {
            data:''
        }
    }

}
</script>

<style>

</style> -->

<!-- ///////////////// Non Props Data/////////// -->

<!-- <template>
  <h2>Non-Props Data</h2>
  <div>
    <h3>Ali</h3>
    <h3>Yas</h3>
    <h3>Oun</h3>
    {{data}}
  </div>

  <p>Has published books:</p>
  <span>{{ publishedBooksMessage }}</span>

</template>

<script>
export default {
 
    const author = reactive({
  name: 'John Doe',
  books: [
    'Vue 2 - Advanced Guide',
    'Vue 3 - Basic Guide',
    'Vue 4 - The Mystery'
  ]
})

// a computed ref
const publishedBooksMessage = computed(() => {
  return author.books.length > 0 ? 'Yes' : 'No'
})
}
</script>

<style>

</style> -->

<!-- <template>
    <h2>Non-Props Data</h2>
    <div>
      <h3>Ali</h3>
      <h3>Yas</h3>
      <h3>Oun</h3>
      {{ data }}
    </div>
  
    <p>Has published books:</p>
    <span>{{ publishedBooksMessage }}</span>
  </template>
  
  <script>
  import { reactive, computed } from 'vue';
  
  export default {
    setup() {
      const author = reactive({
        name: 'John Doe',
        books: [
          'Vue 2 - Advanced Guide',
          'Vue 3 - Basic Guide',
          'Vue 4 - The Mystery'
        ]
      });
  
      const publishedBooksMessage = computed(() => {
        return author.books.length > 0 ? 'Yes' : 'No';
      });
  
      return {
        author,
        publishedBooksMessage
      };
    }
  };
  </script>
  
  <style>
  /* Add your styles here if needed */
  </style> -->

<!-- ////////////Computed Proprty//////////// -->

<!-- <template>
  <h2>Computed Property</h2>
  <h3>{{ getResult }}</h3>
  <h3>{{ getResult }}</h3>
  <h3>{{ getResult }}</h3>
  
</template>

<script>

export default {

  data(){
    return {
      dollor: 100,
      ruppee: 12.5,
      discount:18
    }

  },
  computed:{
    getResult(){

      return(this.dollor*this.ruppee)-this.discount;

        }
  }
}
</script>

<style>

</style> -->

<!-- /////////Watcher/////////////// -->

<!-- <template>
  <h1>{{ count }}</h1>
  <button v-on:click="count=count+1"> + </button>
  <button v-on:click="count=count-1"> - </button>
</template>

<script>
export default {
data(){
  return{
    count:0
  }
},
  watch:{
    count(){
      alert("Value Changed")
    }
  }
}
</script>

<style>

</style> -->