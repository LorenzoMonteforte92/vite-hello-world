<script>
    export default {
        name: 'AppTitle',

        data(){
            return{
                isOriginalTitle: true
            }
        },
        methods: {
            tileChange(){
                this.isOriginalTitle = !this.isOriginalTitle
            }
        }
    }

    
</script>

<template>
  <h1 v-if="isOriginalTitle" >Hello World</h1>
  <h1 v-else >Hello New World</h1>
  <button @click="tileChange()" >Click me</button>
</template>

<style>
h1{
    text-align: center;
    color:rgb(162, 218, 237);
    font-size: 60px;
    margin: 0;
    

}

button {
    margin: auto;
    padding: 10px;
    margin-bottom: 10px;
    background-color: aquamarine;
    border-radius: 10px;
    border: none;
    cursor: pointer;
}
</style>
