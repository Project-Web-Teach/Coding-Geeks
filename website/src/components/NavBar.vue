<template>
    <nav>
        <div class="menu">
            <div class="logo">
                <a> Project Web Teach </a>
            </div>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/languages">Languages</a></li>
                <li><a href="/courses">Courses</a></li>
                <li><a href="/feedback">Feedback</a></li>
            </ul>
            <i
                class="fa-solid fa-bars bars text-2xl"
                style="color: #d8dee9; display: none"
            ></i>
        </div>
    </nav>
</template>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css');

nav {
    position: fixed;
    background: #2e3440;
    width: 100%;
    padding: 10px 0;
    z-index: 12;
}

nav .menu {
    max-width: 90%;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 50px;
}

.menu .logo a {
    text-decoration: none;
    color: #d8dee9;
    font-size: 20px;
    margin-left: 40px;
}

.menu ul {
    display: inline-flex;
}

.menu ul li {
    list-style: none;
    margin-left: 7px;
}

.menu ul li:first-child {
    margin-left: 0px;
}

.menu ul li a {
    text-decoration: none;
    color: #d8dee9;
    font-size: 18px;
    font-weight: 500;
    padding: 10px 15px;
    border-radius: 5px;
    margin-right: 10px;
    transition: all 0.3s ease;
}

.menu ul li a:hover {
    background: #d8dee9;
    color: #2e3440;
}

@media screen and (max-width: 950px) {
    .menu ul {
        display: none;
    }

    .bars {
        display: block !important;
        cursor: pointer;
    }
}
</style>
