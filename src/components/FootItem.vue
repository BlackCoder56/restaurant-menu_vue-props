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
                required: true, // Required Props
                default: 'This is the default price.' // We can set a default value for a prop that show if value is not set.
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