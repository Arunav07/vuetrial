<template>
    <div class="Contaier">
        <div class="container-fluid">
            <h3 class="heading">Hello</h3>
            <div class="leftContainer">
                <ul>
                    <li class="link">Facebook</li>
                    <li class="link">Apple</li>
                    <li class="link">Amazon</li>
                    <li class="link">NETFLIX</li>
                    <li class="link">GOOGLE</li>
                    <li class="link">MICROSOFT</li>
                </ul>
            </div>
            <div class="rightContainer"></div>
        </div>
    </div>
</template>



<style scoped>
.contianer-fluid{
    width: 90vw;
    background: #4f4f4f;
    border-radius: 50px
}
h3.heading{
    color: #323232;
    font-family: SF Pro Display;
    font-weight: 300;
    text-align: center;
}
ul li{
    list-style: none;
    font-weight: 500;
    font-family: SF PRO DISPLAY;
    text-align: center;
    text-transform: uppercase;
    color: #e0b8fa;
    font-size: 22px;
    cursor: pointer;
}
ul{
    justify-content: space-evenly;
    display: flex;
    padding: 5%
}
</style>