<!-- <template>
<h2>ClassBin</h2>
<h3 :class="{green:colorfull}">Class Binding</h3>
<h3 :class="applyStyle">Class Binding</h3>
<button v-on:click="colorfull=!colorfull">Apply On</button>
</template>

<script>
export default {
    name: "ClassBin",
    data() {
        return {
            colorfull: true,
        }
    },
    computed: {
        applyStyle() {
            return {
                green: this.colorfull,
                err: true,
                other: true,
            }
        }
    }
}
</script>

<style scope>
.green {
    background-color: blue;
    width: 300px;
    padding: 10px;
}
.err{
    color: red;
}
.other{
    font-size: 50px;
}
</style> -->
