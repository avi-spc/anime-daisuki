<template>
    <div class="uk-section uk-section-secondary uk-light">
        <div class="uk-container">
            <div class="uk-grid-match uk-child-width-1-3@m uk-text-center footer-grid" uk-grid>
               
                <div class="uk-align-center github-source">
                    <a href="https://github.com/avi-spc/anime-daisuki" class="github-link">
                        <img src="../assets/github-character.svg" alt="" height="48px" width="48px">
                    </a>
                </div>
               
            </div>
            <div class="copyright">
                Made with
                    <img src="../assets/hearts.svg" alt="" height="32px" width="32px">
                by Monster and Starkblaze | &copy Copyright 2019
            </div>
        </div>
    </div>
</template>

<script>
import UIkit from 'uikit';
UIkit.grid(document.getElementsByClassName('footer-grid'));

export default {
    name: "Footer"    
};
</script>

<style lang="scss" scoped>
.github-source{
    margin-bottom: 1%;
}
</style>


