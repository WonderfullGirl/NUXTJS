<template>
    <header class="header">header</header>
    <div class="container">
        defualt layout 
        <slot />
    </div>
    <footer class="footer">footer</footer>
</template>

<style>
.header{
    height: 100px;
    padding-top: 20px;
    background-color: antiquewhite;
    border-bottom: 1px solid #aaaaa7;
    text-align: center;

}
.container{
    margin-top: 20px;
    padding-top: 20px;
    height: 300px;
    background-color: azure;
    text-align: center;

}
.footer{
    margin-top: 20px;
    padding-top: 20px;
    height: 100px;
    background-color:antiquewhite;
    text-align: center;
}
</style>