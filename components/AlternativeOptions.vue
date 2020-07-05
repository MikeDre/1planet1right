<template>
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
</template>

<style lang="scss" scoped>
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
