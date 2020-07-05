<template>
  <div>
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

    <section id="campaign-overview" class="overview uk-padding-large">
        <div class="uk-container">
            <div class="header">
                <h2 class="u-font-heading u-uppercase uk-text-center u-color-primary uk-margin-large-bottom u-bold">Campaign overview</h2>
            </div>
            <div class="uk-grid uk-child-width-1-2@m" uk-grid>
                <div class="uk-text-left@m uk-text-center">
                    <span class="pullquote u-color-primary u-font-primary-bold">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
                    </span>
                </div>
                <div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolr adipiscing elit, sed do eiusmod tempor incididunr adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolr adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolt ut labore et dolr adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="sign-the-petition" class="sign-the-petition uk-padding-large uk-background-cover">
        <div class="uk-container">
            <div class="header">
                <h2 class="u-font-heading u-uppercase uk-text-center u-color-white uk-margin-large-top uk-margin-large-bottom u-bold">Sign the petition</h2>
            </div>
            <div class="uk-grid uk-child-width-1-2@m" uk-grid>
                <div></div>
                <div>
                    <div class="u-background-color-primary">
                        <script type="text/javascript" src="/policat.js"></script>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="alternative-option uk-padding-large">
        <div class="uk-container">
            <div class="header">
                <h5 class="uk-text-center u-color-primary uk-margin-medium-bottom"><strong>You can also sign the petition here:</strong></h5>
            </div>
            <div class="uk-grid uk-child-width-1-6@m uk-child-width-1-1 uk-flex uk-flex-center" uk-grid>
                <div class="uk-text-center">
                    <img src="~/assets/imgs/avaaz.png" alt="Change Org Logo" class="alternative-option__logo">
                </div>
                <div class="uk-text-center">
                    <img src="~/assets/imgs/change-org.png" alt="Change Org Logo" class="alternative-option__logo">
                </div>
            </div>
        </div>
    </section>

    <section class="footer u-background-color-primary u-color-white">
        <div class="uk-padding-large">
            <div class="uk-container">
                <div class="uk-text-center uk-grid uk-child-width-1-2@m" uk-grid>
                    <div>
                        <h2 class="u-font-heading u-uppercase u-color-secondary">Share the petition</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore and dolore magna aliqua.</p>
                        <div class="uk-margin-small-bottom">
                            <a href="#">
                                <button class="btn u-background-color-secondary u-color-white u-uppercase">Share on Facebook</button>
                            </a>
                        </div>
                        <div class="uk-margin-small-bottom">
                            <a href="#">
                                <button class="btn u-background-color-secondary u-color-white u-uppercase">Share on Twitter</button>
                            </a>
                        </div>
                        <div class="uk-margin-medium-bottom">
                            <a href="#">
                                <button class="btn u-background-color-secondary u-color-white u-uppercase">Share via Email</button>
                            </a>
                        </div>
                        <div class="uk-margin-small-bottom">
                            <a href="#">
                                <i class="u-color-secondary fas fa-link"></i> <strong class="u-uppercase u-color-white">Copy link to clipboard</strong>
                            </a>
                        </div>
                    </div>
                    <div>
                        <h2 class="u-font-heading u-uppercase u-color-white">Find our more</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore and dolore magna aliqua.</p>
                        <div class="uk-margin-small-bottom">
                            <a href="#">
                                <button class="btn u-background-color-white u-color-primary u-uppercase">Further reading</button>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="uk-grid uk-child-width-1-2@m" uk-grid>
            <div>
                <div class="uk-padding-large uk-text-left@m uk-text-center">
                    <div class="uk-margin-remove-top@m uk-margin-remove-bottom@m uk-margin-large-bottom">
                        <strong>This petition is supported by over 90 global organisations including:</strong>
                    </div>
                    <div class="uk-margin-large-top uk-margin-large-bottom">
                        <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1" uk-slider="autoplay: true; autoplay-interval: 3000; pause-on-hover: false">
                            <ul class="uk-slider-items uk-child-width-1-2 uk-child-width-1-4@m uk-grid">
                                <li>
                                    <img src="~/assets/imgs/birdlife-international.svg" alt="BirdLife International Logo">
                                </li>
                                <li>
                                    <img src="~/assets/imgs/global-pact.svg" alt="Global Pact Logo">
                                </li>
                                <li>
                                    <img src="~/assets/imgs/client-earth.svg" alt="Client Earth Logo">
                                </li>
                                <li>
                                    <img src="~/assets/imgs/client-earth.svg" alt="Client Earth Logo">
                                </li>
                                <li>
                                    <img src="~/assets/imgs/birdlife-international.svg" alt="BirdLife International Logo">
                                </li>
                                <li>
                                    <img src="~/assets/imgs/global-pact.svg" alt="Global Pact Logo">
                                </li>
                                <li>
                                    <img src="~/assets/imgs/client-earth.svg" alt="Client Earth Logo">
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div>&copy; 2020 BirdLife International One Planet One Right. All Rights Reserved</div>
                </div>
            </div>
            <div class="uk-text-right@m uk-text-center">
                <img class="uk-visible@m" src="~/assets/imgs/globe-image.png" alt="Image of a turtle">
                <img class="uk-hidden@m" src="~/assets/imgs/globe-image-mobile.png" alt="Image of a turtle">
            </div>
        </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

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

.text-highlight {
    background-color: #ffd3006e;
    padding: 0 5px;
}

.btn {
    border: 0;
    clip-path: polygon(90% 0, 100% 18%, 98% 94%, 0 100%, 1% 0);
    font-weight: 700;
    font-family: $font-primary-bold;
    padding: 10px 20px;
}

.pullquote {
    font-weight: 700;
    font-size: 32px;
}

.sign-the-petition {
    background-image: url('~assets/imgs/bird-bg.jpg');
    min-height: 500px;
    overflow-x: hidden;
    position: relative;

    &:before {
        background-color: color('white');
        content: '';
        height: 50px;
        left: 0;
        position: absolute;
        top: 0;
        transform: rotate(1deg) translate3d(-10px, -20px, 0);
        width: 110%;
    }
}

.alternative-option {
    overflow-x: hidden;
    position: relative;

    &:before {
        background-color: color('white');
        content: '';
        height: 50px;
        left: 0;
        position: absolute;
        top: 0;
        transform: rotate(-1deg) translate3d(-10px, -20px, 0);
        width: 110%;
    }
}

.alternative-option__logo {

    @include mq($until: desk) {
        max-width: 200px;
    }
}
</style>
