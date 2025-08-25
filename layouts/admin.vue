<template>
    <header class="header">header</header>
    <div class="container">
        defualt layout Admin
        <slot />
    </div>
    <footer class="footer">footer</footer>
</template>

<style>
.header{
    height: 100px;
    padding-top: 20px;
    background-color: rgb(238, 155, 47);
    border-bottom: 1px solid #aaaaa7;
    text-align: center;

}
.container{
    margin-top: 20px;
    padding-top: 20px;
    height: 300px;
    background-color: rgb(153, 240, 157);
    text-align: center;

}
.footer{
    margin-top: 20px;
    padding-top: 20px;
    height: 100px;
    background-color: rgb(238, 155, 47);
    text-align: center;
}
</style>