<template>
    <div class="bg-white">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex flex-column align-items-center">
                    <h1>Latest News & Our <span>Blog</span></h1>
                    <div class="line-small line-gradient rounded-pill">
                        <div class="line-big line-gradient rounded-pill"></div>
                    </div>
                </div>
                
                <CardBlog/>

                <div class="text-center">
                    <button class="button button-secondary">View all post</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import CardBlog from '../Card/CardBlog.vue';

export default {

    components: {
        CardBlog,
    },

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    h1{
        font-size: 50px;
        font-weight: 600;
        letter-spacing: -3px;
        line-height: 60px;

        span{
            color: $tertiaryColorBrand;
        }
    }

    .button-secondary{
        background: linear-gradient(90deg, $primaryColorBg, $secondaryColorBg);

        &:hover{
            box-shadow: 0 8px 20px rgba($secondaryColorBg, $alpha: 0.3);
        }
    }

</style>