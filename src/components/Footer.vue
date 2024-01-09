<template>
    <div class="container-fluid">
        <div class="row">
            <p class="lead">
                Thimna's Portfolio &copy;
                <span>{{ currYear }}</span>
            </p>
        </div>

    </div>
</template>

<script>
    export default {
        name:'FooterComp',
        data(){
            return{
                currYear: new Date().getFullYear()
            }
        }
        
    }
</script>

<style scoped>

</style>