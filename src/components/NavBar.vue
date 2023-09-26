<template>
    <div class="navbar">
        <ul id="left-bar">
            <li>About us</li>
            <li>FAQ</li>
        </ul>

        <ul id="right-bar">
            <button id="login-btn">Get Started</button>
        </ul>
    </div>
</template>

<script setup>

</script>

<style scoped>
    .navbar{
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: 15px;
        font-family: 'Roboto', sans-serif;
        list-style: none;
        color: #fff;
        background-color: #111827a2;
        height: 60px;
        text-align: center;
    }

    #left-bar{
        display: flex;

    }
    #left-bar li{
        list-style: none;
        margin-left: 20px;
    }

    #right-bar{
        display: flex;
        justify-content: space-around;
        margin: 20px;
        align-items: center;
    }

    #right-bar li{
        list-style: none;
        margin-right: 40px;
    }

    #login-btn {
    width: 140px;
    align-items: center;
    background-image: linear-gradient(135deg, #432bd9 40%, #ef3838);
    border: 0;
    border-radius: 10px;
    box-sizing: border-box;
    color: #fff;
    cursor: pointer;
    display: flex;
    flex-direction: column;
    font-family: "Codec cold",sans-serif;
    font-size: 12px;
    font-weight: 700;
    height: 44px;
    justify-content: center;
    letter-spacing: .4px;
    line-height: 0.7;
    max-width: 100%;
    padding-left: 20px;
    padding-right: 20px;
    padding-top: 3px;
    text-decoration: none;
    text-transform: uppercase;
    user-select: none;
    -webkit-user-select: none;
    touch-action: manipulation;
    }

    #login-btn:active {
    outline: 0;
    }

    #login-btn:hover {
    outline: 0;
    }

    #login-btn span {
    transition: all 200ms;
    }

    #login-btn:hover span {
    transform: scale(.9);
    opacity: .75;
    }

    @media screen and (max-width: 991px) {
    #login-btn {
        font-size: 15px;
        height: 50px;
    }

    #login-btn span {
        line-height: 50px;
    }
    }
</style>