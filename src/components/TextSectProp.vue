<template>
    <div id="first-inner-contents">
        <h2>{{ headingText }}</h2> <!-- Fixed casing here -->
        <p>{{ headingPara }}</p> <!-- Fixed casing here -->
        <div>
            <button id="learn-more">{{ learnMore }}</button> <!-- Fixed casing here -->
            <button id="buy">{{ buy }}</button> <!-- Fixed casing here -->
        </div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue';

defineProps({
    headingText: {
        type: String,
        default: 'iPhone 16 Pro'
    },
    headingPara: {  
        type: String,
        default: 'Hello, Apple Intelligence.'
    },
    learnMore: {    
        type: String,
        default: 'Learn More'
    },
    buy: {          
        type: String,
        default: 'Buy'
    }
});
</script>
