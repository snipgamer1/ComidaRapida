<template>
    <div class="col">
        <div class="card text-center" style="width: 18rem;">
            <slot></slot>  
            <div class="card-body">
                <h5 class="text-center"> {{ titulo }} </h5>
                <p class="text-center"> {{ nombre }}.</p>
                <p class="text-center"> {{ descripsion }} </p>
                <p class="text-center"> {{ precio }} </p>
            </div>
        </div>
    </div>
</template>   

<script>

    export default {
        props: {
            titulo: {
                String,
            },
            nombre: {
                String,
            },
            descripsion: {
                String,
            },
            precio: {
                String,
            },
        },


    };
</script>

<style scoped>
    img{
        width: 18rem;
        height: 9rem;
        display: inline-block;
    }
    
</style>