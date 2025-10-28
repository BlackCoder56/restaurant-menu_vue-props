<template>
   <div>
    {{ foodName }} .............. {{ foodPrice }}
   </div>
</template>

<script>
    export default {
        props: [
            'foodName',
            'foodPrice'
        ]
        // data() {
        //     return {
        //         name: 'Chips',
        //         price: '$4.0'
        //     }
        // }
    };
</script>