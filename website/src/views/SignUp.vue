<template>
<div class="wrapper">
    <div class="container" id="container">
        <div class="form-container log-in-container">

            <form action="#">
                <h1>
                    Sign Up
                </h1>

                <div class="social-container">
                    <a href="#" class="social">
                        <i class="fas fa-facebook fa-2x"></i>
                    </a>

                    <a href="#" class="social">
                        <i class="fas fa-twitter fa-2x">
                        </i>
                    </a>
                </div>

                <span>
                    or enter credentials
                </span>


                <input type="email" placeholder="Enter your email" />
                <input type="password" placeholder="Choose a password" />

                <br>
                
                <button>
                    Log In
                </button>
            </form>
        </div>

        <div class="overlay-container">
            <div class="overlay">
                <div class="overlay-panel overlay-right">
                    <h1>
                        Coding Geeks
                    </h1>

                    <p>
                        Everyone is once a learner, Now's just the right time to start!
                    </p>

                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    setup() {

    },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,800');


h1 {
    font-weight: bold;
    margin: 0;
}

p {
    font-size: 14px;
    font-weight: 100;
    line-height: 20px;
    letter-spacing: 0.5px;
    margin: 20px 0 30px;
}

span {
    font-size: 12px;
}

a {
    color: #88C0D0;
    font-size: 14px;
    text-decoration: none;
    margin: 15px 0;
}

button {
    border-radius: 20px;
    border: 1px solid #Bf616A;
    background-color: #Bf616A;
    color: #FFFFFF;
    font-size: 12px;
    font-weight: bold;
    padding: 12px 45px;
    letter-spacing: 1px;
    text-transform: uppercase;
    transition: transform 80ms ease-in;
}

form {
    background-color: #3B4252;
    display: flex;
    align-items: center;
	color: #D8DEE9;
    justify-content: center;
    flex-direction: column;
    padding: 0 50px;
    height: 100%;
    text-align: center;
}

input {
    background-color: #434C5E;
	outline: none;
	color: #D8DEE9;
    border: none;
    padding: 12px 15px;
    margin: 8px 0;
    width: 100%;
	border-radius: 5px;
	font-size: 15px;
}

.container {
    background-color: #434C5E;
    border-radius: 10px;
    position: relative;
    overflow: hidden;
    width: 768px;
    max-width: 100%;
    min-height: 480px;
}

.form-container {
    position: absolute;
    top: 0;
    height: 100%;
}

.log-in-container {
    left: 0;
    width: 50%;
    z-index: 2;
}

.overlay-container {
    position: absolute;
    top: 0;
    left: 50%;
    width: 50%;
    height: 100%;
}

.overlay {
    background: #88C0D0;
    background: -webkit-linear-gradient(to right, #8FBCBB, #88C0D0, #81A1C1);
    background: linear-gradient(to right, #8FBCBB, #88C0D0, #81A1C1);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 0 0;
    color: #2E3440;
    position: relative;
    left: -100%;
    height: 100%;
    width: 200%;
}

.overlay-panel {
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    top: 0;
    height: 100%;
    width: 50%;
}

.overlay-right {
    right: 0;
}

.social-container {
    margin: 50px 0;
}

.social-container a {
    border: 1px solid #DDDDDD;
	background-color: #3B4252;
    border-radius: 50%;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    margin: 0 5px;
    height: 40px;
    width: 40px;
}

.wrapper {
	width: 100vw;
	height: 100vh;
	display: flex;
	align-items: center;
	justify-content: center;
}
</style>
