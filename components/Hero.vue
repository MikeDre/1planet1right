<template>
    <section class="hero u-background-color-primary uk-background-cover">
        <div class="uk-container uk-text-center">
            <div class="hero__lockup">
                <div class="hero__logo uk-margin-large-top">
                    <Logo />
                </div>
                <div class="hero__caption u-color-white uk-margin-large-bottom u-font-primary-bold">
                    Let's make it a <span class="u-text-highlight">human right</span><br>
                    to live on a <span class="u-text-highlight">healthy planet</span>
                </div>
            </div>
            <div class="hero__cta uk-margin-large-bottom u-font-heading">
                <button class="btn u-background-color-white u-color-primary u-uppercase uk-margin-small-left uk-margin-small-right">Campaign overview</button>
                <button class="btn u-background-color-secondary u-color-white u-uppercase uk-margin-small-left uk-margin-small-right">Sign the petition</button>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.hero {
    background-image: url('~assets/imgs/planet-hero.jpg');
    background-origin: content-box;
    background-position: bottom center;
    background-size: contain;
}

.hero__caption {
    font-size: 30px;
    transform: rotate(-11deg) translateX(120px);
}

.hero__lockup {
    transform: translateX(-100px);
}
</style>
