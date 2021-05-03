<template>
<div class="inner-block2">
    <div class="vue-tempalte">
        <form class = "formcolor">      
            
            <div class="form-group">
                <label class="textstyles">Enter Your Username</label>
                <input type="username" class="form-control form-control-lg" />
            </div>

            <div class="form-group">
                <label class="textstyles">Password</label>
                <input type="password" class="form-control form-control-lg" />
            </div>

            <button id ="textstyles" type="submit" class="btn btn-dark btn-lg btn-block" >SIGN IN AS DRIVER</button>

            <p class="forgot-password text-right mt-2 mb-4" id="forgottext" >
                <router-link to="/forgot-password"  id="forgottext">Forgot password ?</router-link>
            </p>

           

        </form>
    </div>
</div>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>
<style>
   
</style>
