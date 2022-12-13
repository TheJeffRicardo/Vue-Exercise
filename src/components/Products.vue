<template>
    <h1>This is the Product Page</h1>
    <div v-for="item in products" :key="item">
        <p>{{item.name}}</p>
    </div>
</template>
<script> 
export default{
    name: 'product',
    data() {
        return {
            products: [
                {
                    name: 'Konke'
                },
                {
                    name: 'Jeff'
                },
                {
                    name: 'Jack'
                },
                {
                    name: 'Kitty'
                },
                {
                    name: 'Adam'
                },
            ]
        }
    }
}
</script>

<style>
p{
    padding-top: 10px;
}
</style>