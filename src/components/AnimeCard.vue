<template>
    <div class="uk-section">
        <div class="uk-container">
           <div uk-grid>
            <div class="uk-width-1-3@m card-grid">
                <div class="uk-card uk-card-secondary uk-card-hover uk-light">
                    <div class="uk-card-media-top">
                        <img src="../assets/8040.jpg" alt="">
                    </div>
                    <div class="uk-card-body">
                        <h3 class="uk-card-title uk-text-left">Media Top</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
            </div>
            <div class="uk-width-1-3@m card-grid">
                <div class="uk-card uk-card-secondary uk-card-hover uk-light">
                    <div class="uk-card-media-top">
                        <img src="../assets/8040.jpg" alt="">
                    </div>
                    <div class="uk-card-body">
                        <h3 class="uk-card-title uk-text-left">Media Top</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
            </div>
            <div class="uk-width-1-3@m card-grid">
                <div class="uk-card uk-card-secondary uk-card-hover uk-light">
                    <div class="uk-card-media-top">
                        <img src="../assets/8040.jpg" alt="">
                    </div>
                    <div class="uk-card-body">
                        <h3 class="uk-card-title uk-text-left">Media Top</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
            </div>
            <div class="uk-width-1-3@m card-grid">
                <div class="uk-card uk-card-secondary uk-card-hover uk-light">
                    <div class="uk-card-media-top">
                        <img src="../assets/8040.jpg" alt="">
                    </div>
                    <div class="uk-card-body">
                        <h3 class="uk-card-title uk-text-left">Media Top</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
    </div>
</template>

<script>
import UIkit from 'uikit';
UIkit.grid(document.getElementsByClassName('card-grid'));

export default {
    name: "AnimeCard"    
};
</script>

<style lang="scss" scoped>
.anime-card{
    display: inline-block;
}
</style>
