<script setup lang="ts"></script>

<template>
    <div class="_container">
        <div class="img">
            <img src="" alt="" />
        </div>
        <div class="center">
            <div class="wrapper">
                <div class="title">Project Web Teach</div>
                <div class="sub_title">
                    Everyone is once a learner, Now's just the right time to
                    start!
                </div>
                <br />
                <div class="btns">
                    <button>
                        <a href="/signup" style="margin-right: 10px"
                            ><i class="fas fa-meteor"></i></a
                        >Arch>
                    </button>
                    <button>
                        <a href="/login" style="margin-right: 10px">Login</a>>
                    </button>
                </div>
            </div>
            <i class="fa-solid fa-bars absolute text-white text-7xl"></i>
        </div>
    </div>
</template>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Comfortaa';
}

::selection {
    color: #2e3440;
    background: #d8dee9;
}

a {
    text-decoration: none;
}

.img::before {
    content: '';
    position: absolute;
    background: #2e3440;
}

.center {
    display: flex;
    height: 90vh;
    background-color: #2e3440;
    align-items: center;
    justify-content: center;
}

.center .title {
    color: #d8dee9;
    font-size: 40px;
    text-align: center;
    margin-bottom: 20px;
}

.center .sub_title {
    color: #d8dee9;
    font-size: 25px;
    text-align: center;
}

.center .btns {
    margin-top: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.center .btns button {
    height: 55px;
    width: 170px;
    border-radius: 5px;
    border: none;
    margin: 0 10px;
    border: 2px solid white;
    font-size: 20px;
    font-weight: 500;
    padding: 0 10px;
    cursor: pointer;
    outline: none;
    transition: all 0.3s ease;
}

.center .btns button:first-child {
    color: #d8dee9;
    background: none;
}

.btns button:first-child:hover {
    background: white;
    color: #2e3440;
}

.center .btns button:last-child {
    background: white;
    color: #2e3440;
}
</style>
