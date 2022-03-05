<template>
<nav>
    <div class="menu">
        <div class="logo">
            <a> Project Web Teach </a>
        </div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Languages</a></li>
            <li><a href="#">Cources</a></li>
            <li><a href="#">Feedback</a></li>
        </ul>
    </div>
</nav>
</template>

<style scoped>

nav {
    position: fixed;
    background: #2E3440;
    width: 100%;
    padding: 10px 0;
    z-index: 12;
}

nav .menu {
    max-width: 1250px;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 50px;
}

.menu .logo a {
    text-decoration: none;
    color: #D8DEE9;
    font-size: 25px;
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
    color: #D8DEE9;
    font-size: 18px;
    font-weight: 500;
    padding: 10px 15px;
    border-radius: 5px;
    margin-right: 10px;
    transition: all 0.3s ease;
}

.menu ul li a:hover {
    background: #D8DEE9;
    color: #2E3440;
}


</style>
