<template>
    <nav class="uk-navbar-container uk-light navbar" uk-navbar>
        <div class="uk-navbar-center">
            <div class="uk-navbar-center-left">
                <ul class="uk-navbar-nav">
                    <li class="uk-active"><a href="#">Home</a></li>
                    <li class="uk-active"><a href="#">About</a></li>
                </ul>
            </div>
            <a class="uk-navbar-item uk-logo" href="#">
                <img src="../assets/anime-character.svg" alt="" height="48px" width="48px">
                <div uk-text-center uk-text-middle>
                    Anime <img src="../assets/hearts.svg" alt="" height="16px" width="16px">   Daisuki
                </div> 
            </a>
            <div class="uk-navbar-center-right">
                <ul class="uk-navbar-nav">
                    <li class="uk-active"><a href="#">Home</a></li>
                    <li class="uk-active"><a href="#">About</a></li>
                </ul>
            </div>
        </div>
        <div class="uk-navbar-right">
            <ul class="uk-navbar-nav">
                <div class="uk-navbar-item">
                    <form action="javascript:void(0)">
                        <button class="uk-button uk-button-default" uk-tooltip="title: Hello World; pos: bottom-right">Login/Signup</button>
                    </form>
                </div>
            </ul>
        </div>
    </nav>
</template>

<script>
import UIkit from 'uikit';
UIkit.navbar(document.getElementsByTagName('nav'));

export default {
    name: "NavBar"    
};
</script>

<style lang="scss" scoped>
.navbar{
    background: #424242;
}
</style>


