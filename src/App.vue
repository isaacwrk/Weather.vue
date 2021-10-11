<template>
  <div id="app">
    <main>
    <div class="search-box">
        <input type="text" class="search-bar" placeholder="Pesquisar.." />
    </div>
</main>
  </div>
</template>

<script>
export default {
    name:'app',
    data(){
        return{
            api_key:'1e98200976dfc0825963c51093ac8a88'
        }
    }

}
</script>

<style>

*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
}

body{
    font-family: 'montserrat', sans-serif;
}

</style>

