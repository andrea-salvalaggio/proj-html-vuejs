<template>
    <div class="tertiary-bg">
        <div class="container padding-tb">
            <div class="row">
                <div class="col-4">
                    <h1 class="mb-4">With <span>Live Chat 24/7</span> Support</h1>
                    <div class="line-small line-gradient rounded-pill">
                        <div class="line-big line-gradient rounded-pill"></div>
                    </div>
                    <p class="mb-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum reiciendis alias totam consequatur magni minus officiis vero distinctio, quos molestias iste, quidem nihil porro maiores expedita.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    .tertiary-bg{
        background-color: $tertiaryColorBg;
        position: relative;
    }

    h1{
        font-size: 50px;
        font-weight: 600;
        letter-spacing: -3px;
        line-height: 60px;

        span{
            color: $tertiaryColorBrand;
        }
    }

    p{
        margin-top: 40px;
        color: $secondaryColorText;
    }

    .padding-tb{
       padding: 200px 0;
    }


</style>