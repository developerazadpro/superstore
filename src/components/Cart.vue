<template>
    <ul class="list-group">
        <li class="list-group-item">
            <span class="item-name"><b>Name</b></span>
            <span class="item-price float-right"><b>Price</b></span>
        </li>
        <hr>

        <li v-for="(item, index) in items" :key="index" class="list-group-item">
            <span class="item-name">{{ item.title }}</span>
            <span class="item-price float-right">${{ item.price }}</span>
        </li>
        <hr>
        <li class="list-group-item">
            <span class="item-name"><b>Total</b></span>
            <span class="item-price float-right"><b>${{ totalPrice }}</b></span>
        </li>
    </ul>
</template>

<script>
    export default {
        props:['items'],
        computed: {
            totalPrice(){
                var total = 0
                this.items.forEach(item => {
                    total += parseFloat(item.price)
                })
                return parseFloat(total)
            }
        }
    }
</script>

<style>

</style>