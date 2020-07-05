<template>
    <section class="hero u-background-color-primary uk-background-cover">
        <div class="uk-container uk-text-center">
            <div class="hero__lockup">
                <div class="hero__logo uk-margin-large-top">
                    <Logo class="uk-visible@s" />
                    <LogoMobile class="uk-hidden@s" />
                </div>
                <div class="hero__caption u-color-white uk-margin-large-bottom u-font-primary-bold">
                    Let's make it a <span class="text-highlight">human right</span><br>
                    to live on a <span class="text-highlight">healthy planet</span>
                </div>
            </div>
            <div class="hero__cta uk-margin-large-bottom u-font-heading">
                <a class="hero__cta--campaign" href="#campaign-overview" uk-scroll>
                    <button class="btn u-background-color-white u-color-primary u-uppercase uk-margin-small-left uk-margin-small-right">Campaign overview</button>
                </a>
                <a class="hero__cta--petition" href="#sign-the-petition" uk-scroll>
                    <button class="btn u-background-color-secondary u-color-white u-uppercase uk-margin-small-left uk-margin-small-right">Sign the petition</button>
                </a>
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

    @include mq($until: desk) {
        background-image: url('~assets/imgs/planet-hero-mobile.jpg');
        background-position: center 70%;
    }
}

.hero__caption {
    font-size: 26px;
    transform: rotate(-11deg) translateX(120px);

    @include mq($until: desk) {
        transform: rotate(-11deg) translateX(0);
    }
}

.hero__lockup {
    transform: translateX(-100px);

    @include mq($until: desk) {
        transform: translateX(0);
    }
}

.hero__cta {

    @include mq($until: desk) {
        margin-top: 200px;
    }
}

.hero__cta--campaign {

    @include mq($until: desk) {
        display: block;
        margin-bottom: 10px;
    }
}
</style>
