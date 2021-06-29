
<template>
<div>
    <button class="button"> 
        <h1>Yes</h1>
    </button>

    <button class="button"> 
        <h1>No</h1>
    </button>
</div>
</template>



<script setup>
export default {
    props: {
        text: {
            type: String,
            default: 'Click Here'
        }
    }
}

</script>