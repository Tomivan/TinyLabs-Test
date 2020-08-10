<template>
    <div id="signup-page" class="container">
        <img alt="" src="../assets/Bitmap.png" class="bitmap">
        <div class="signup">
            <h2> Create your free account</h2>
            <p> Already Registered? <span> Sign in </span></p>
            <div class="signup-form">
                <div class="name">
                    <input type="text" placeholder="First Name">
                    <input type="text" placeholder="Last Name">
                </div>
                <input type="email" placeholder="Email">
                <input type="password" placeholder="Password">
                <button class="continue"> Continue </button>
            </div>
            <footer class="footer">
                <p>By signing up, you agree to our <span>Terms</span> and <span> Privacy Policy</span> </p>
                <p> 2019 TinyLabs. All rights reserved</p>
            </footer>
        </div>
    </div>
</template>

<script>
export default {
    name: 'signup-page'
}
</script>

<style>
.container{
    display: flex;
}
.bitmap {
    height: 100vh;
}
.signup {
    margin-left: 10%;
    margin-top: 5%;
}
</style>