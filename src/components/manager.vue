<template>

    <div class="inner-block1">
        <div class="manager">
        <form class= "formstyles">
            

            <div class="form-group">
                <label class="textstyles2">Enter Your Username</label>
                <input type="username" class="form-control form-control-lg" />
            </div>

            <div class="form-group">
                <label class="textstyles2">Password</label>
                <input type="password" class="form-control form-control-lg" />
            </div>

            <button id ="textstyles" type="submit" class="btn btn-dark btn-lg btn-block" >SIGN IN AS MANAGER</button>

            <p class="forgot-password text-right mt-2 mb-4">
                <router-link to="/forgot-password" style="color: #fff" >Forgot password ?</router-link>
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

    body{
        background-color: white;
    }
</style>
