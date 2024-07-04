<template>
    <div>
        <header>
            <nav>
                <div>
                    <h1>Demo Vue router</h1>
                </div>
                <ul>
                    <router-link to='/'>Home</router-link>
                    <router-link to='/about'>About</router-link>
                    <router-link to='/login'>Login</router-link>
                </ul>
            </nav>
        </header>
    </div>
</template>

<style scoped>
header {
    background-color: brown;
    color: #fff;
}
nav {
    width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
}
</style>