<template>
<div class="home">
    <h1>Homepage</h1>
    <v-btn class="pink white--text" v-on:click ="clickMe()">Click Me</v-btn>
    <v-btn color="pink" depressed dark>Click Me</v-btn>
    <v-btn flat color="pink">Click Me</v-btn>
    <v-btn depressed class="pink whie--text">
        <v-icon left>email</v-icon>   
        <span>Email me</span>     
    </v-btn>
     <v-btn small depressed class="pink whie--text">
        <v-icon small left>email</v-icon>   
        <span>Email me</span>     
    </v-btn>
     <v-btn large depressed class="pink whie--text">
        <span>Email me</span>     
        <v-icon large right>email</v-icon>   
    </v-btn>
     <v-btn fab small depressed dark color="purple">        
        <v-icon> favorite</v-icon>   
    </v-btn>
</div>
</template>
<script lang="ts">
import Vue from 'vue';
export default Vue.extend({
    props:{},
    name: 'home',
    methods: {
        clickMe(){
            alert('hello');
        }
    }
    
});
</script>

