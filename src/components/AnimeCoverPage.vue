<template>
    <div class="uk-section anime-cover-section">
       <!-- <div class="uk-container"> -->
            <div class="anime-cover">
                <div id="test-target" class="uk-height-large uk-background-cover uk-light uk-flex uk-flex-top anime-cover-image" uk-parallax="bgy: -200">
                    <h1 class="uk-width-1-2@m uk-text-left uk-margin-small uk-margin-auto-vertical" uk-parallax="y: 100,0">Toradora</h1>
                </div>
            </div>          
            <!-- <div class="uk-card uk-card-default uk-card-hover uk-card-body uk-width-1-2@m anime-profile-card"> -->
                <!-- <h3 class="uk-card-title">Default</h3>
                <p>Lorem ipsum <a href="#">dolor</a> sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> -->
            <img src="https://media.kitsu.io/anime/poster_images/1/small.jpg?1431697256" alt="" class="card-profile-image uk-card uk-card-default uk-card-hover uk-card-body uk-width-1-2@m">
            <!-- </div>               -->
            <div class="uk-section anime-cover-info">
               <div class="uk-container">
                   <div>                       
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ipsam libero distinctio doloremque optio at. Molestias, eligendi quasi aliquam modi voluptate velit mollitia, excepturi aliquid saepe nulla maiores perferendis consequatur error!
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit fuga illo cupiditate, eaque sapiente soluta repellat minus necessitatibus sequi quaerat totam enim dolores maxime, placeat ut asperiores perspiciatis rerum! Impedit!
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore ab sapiente blanditiis nesciunt nulla ullam illo ipsa debitis at dignissimos ducimus nihil voluptas, fugiat cum maxime, sint necessitatibus, quos amet?
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa, magnam ea! Beatae perferendis ut odit cumque vero repellat a repudiandae molestias tenetur, nemo officiis, veniam consectetur facere nisi? Voluptatum, harum!
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eum maxime temporibus, fugiat accusamus architecto, modi iure harum officiis dolor quas dolore nihil reiciendis ipsa laborum exercitationem. Doloribus eum adipisci fuga.
                        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores a quia dignissimos. Rem, repellat impedit fuga eum laudantium consectetur. Nostrum, laborum maxime! Quos beatae, eum ea consequatur assumenda dolorem quae?
                    </div>
               </div>
           </div>
           
       <!-- </div> -->
    </div>
</template>

<script>
import UIkit from 'uikit';
UIkit.parallax(document.getElementsByClassName('anime-cover'));
UIkit.grid(document.getElementsByClassName('anime-cover-card-grid'));
UIkit.img(document.getElementsByClassName('element'));

export default {
    name: "AnimeCoverPage"    
};
</script>

<style lang="scss" scoped>

.anime-cover{
    height:10%;
}

.anime-cover-image {
    background-image: url("https://media.kitsu.io/anime/cover_images/1/original.jpg?1519178801");
}

.anime-cover-section{
    padding-top: 0px;
    padding-bottom: 0px;
    transform:translateY(0%); 
}
.anime-cover-info{
    //background: #39f;
    margin: 0%;
}

.anime-profile-card{
    padding: 0%;
    max-width: 25%;
    height: 50%;
    transform: translateY(-50%);
}

.card-profile-image{
    padding:0%;
    height: 100%;
    object-fit: contain;
    // width: 100%;
    width: 25%;
    float: left;
    transform: translateY(-50%);
    margin-left: 5%;
}

</style>
