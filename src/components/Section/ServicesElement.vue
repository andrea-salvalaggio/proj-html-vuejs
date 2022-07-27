<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex">
                <div>
                    SINISTRA
                    <h1>We Are Here To Make Your Website Look More Elegant And Stylish!</h1>
                    <div class="line-small line-gradient rounded-pill">
                        <div class="line-big line-gradient rounded-pill"></div>
                    </div>
                    <button class="button button-primary">View all</button>
                </div>
                <div>
                    <CardServices/>
                </div>
                <div>
                    <span>17 years of experience helping people for best solutions</span>
                </div>
            </div>
        </div>     
    </div>
</template>

<script>
import CardServices from '../Card/CardServices.vue';

export default {

    components: {
        CardServices,
    },

}
</script>

<style lang="scss">
@import "../../styles/variables.scss";

    .line-small{
        width: 10px;
        height: 5px;
    }

    .line-big{
        width: 50px;
        height: 5px;
        margin-left: 15px;
    }

    .line-gradient{
        background: linear-gradient(90deg, $secondaryColorBrand, $tertiaryColorBrand);
    }

    .button{
        width: 150px;
        height: 50px;
        font-size: 12px;
        font-weight: 600;
        color:white;
        text-transform: uppercase;
        border: none;
        border-radius: 50px;
    }

    .button-primary{
        background: linear-gradient(90deg, $secondaryColorBrand, $tertiaryColorBrand);

        &:hover{
            box-shadow: 0 8px 20px rgba($primaryColorBrand, $alpha: 0.3);
        }
    }

</style>