<template>
    <h1>This is the Product Page</h1>
    <div v-for="item in products" :key="item">
        <p>{{item.name}} {{item.surname}}</p>
    </div>
</template>
<script> 
export default{
    name: 'product',
    data() {
        return {
            products: [
                {
                    name: 'Konke',
                    surname: 'Malindi'
                },
                {
                    name: 'Jeff',
                    surname: 'Ricardo'
                },
                {
                    name: 'Jack',
                    surname: 'Titanio'
                },
                {
                    name: 'Kitty',
                    surname: 'Tom'
                },
                {
                    name: 'Adam',
                    surname: 'Cole'
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