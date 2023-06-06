<template>
    <div class="container">
        <div class="row">
           <div class="col-md-6">
            <button class="btn btn-lg btn-primary" @click="login">
                <a class="nav-link" href="https://robinsonslandcorporation.site/laravel-test/public/login">Login</a>
            </button>
           </div>
           <div class="col-md-6">
            <button class="btn btn-lg btn-success" @click="register">
                <a class="nav-link" href="https://robinsonslandcorporation.site/laravel-test/public/register">Register</a>
            </button>
           </div>
        </div>
    </div>
    
</template>

<script>
    export default {
        data(){

        },
        methods:{
            login: function(){
                window.location.href="https://robinsonslandcorporation.site/laravel-test/public/login";
            },
            register: function(){
                window.location.href="https://robinsonslandcorporation.site/laravel-test/public/register";
            }

        }

    }
</script>
<style scoped>
</style>

