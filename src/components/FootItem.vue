<template>
   <div>
    {{ foodName }} .............. {{ foodPrice }}
   </div>
</template>

<script>
    export default {
        // Props as an Object
        props: {
            foodName: String,
            foodPrice: {
                type: String,
                required: true // Required Props
            }
        }
        // props: ['foodName', 'foodPrice']
        // data() {
        //     return {
        //         name: 'Chips',
        //         price: '$4.0'
        //     }
        // }
    };
</script>