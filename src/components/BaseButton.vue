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

<script>

export default {
    props: {
        text: {
            type: String,
            required: true
        },
    },
    
    data() {
        return {
            gym: 'Harlem gym',
        }
    },

    methods: {
        addToLog() {
            
        }//create method here
        
    }
}

</script>




