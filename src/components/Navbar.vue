<template>
    <div class="main-nav">
        <ul>
            <li>
                <router-link to="/">Home</router-link>
                <router-link :to="{name: 'About'}">About</router-link>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {

    }
  }
}
</script>

<style >

ul{
    text-decoration: none;
    padding: 0px;
}

a{
    color: darkseagreen;
}

</style>