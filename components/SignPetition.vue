<template>
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
</template>

<style lang="scss" scoped>
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
</style>
