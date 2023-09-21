<script setup>
    import { ref, reactive, computed, watch } from 'vue'
    import '@/assets/style.css';
    
    function say(message) { 
    alert(message)
  }
</script>

<template>
    <h1>Give me feedback!</h1>

    <h2>Will you hire me?</h2>
    <form>
        <input type="radio" id="yes" name="hire me?" value="yes">
        <label for="yes"> Yes </label>
        <input type="radio" id="no" name="hire me?" value="no">
        <label for="no"> No </label><br>
    </form><br>

    <h2>Please enter your name:</h2>
    <p>Thank you! Your name is... {{ messagea }}</p>
    <input v-model.lazy="messagea" placeholder="your name here" />
    <br>
    <h2>Please enter your email:</h2>
    <p>Thank you! Your email is... {{ messageb }}</p>
    <input v-model.lazy="messageb" placeholder="your email here" />
    <br>

    <button @click="say('Your feedback has been submitted')">Submit</button>
</template>