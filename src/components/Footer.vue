<template>
    <div class="container-fluid fixed-bottom">
        <div class="row">
            <p class="lead">
                Thimna's Portfolio &copy;
                <span>{{ currYear }}</span>
            </p>
            <!-- icons -->
            <div class="text-center ">
        <a href="https://www.linkedin.com/in/thimna-alam-117618297?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B9Rrg2YrGQ%2BKI1aZnH0m3tQ%3D%3D" class="text-dark mx-2"><i class="ab fa-linkedin"></i></a>
        <a href="https://github.com/thimnaalam" class="text-dark mx-2"><i class="fab fa-github"></i></a>
         
    </div>
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