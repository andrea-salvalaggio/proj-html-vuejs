<template>
    <div class="container margin-tb">
        <div class="row">
            <div class="col-12 d-flex">
                <div class="services-container">
                    <h1 class="mb-5">We Are Here To Make Your <span>Website</span> Look More <span>Elegant</span> And Stylish!</h1>
                    <div class="line-small line-gradient rounded-pill">
                        <div class="line-big line-gradient rounded-pill"></div>
                    </div>
                    <button class="button button-primary mt-5">View all</button>
                </div>
                <div>
                    <CardServices/>
                </div>
                <div class="side-text">
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

    .services-container{
        h1{
            font-size: 50px;
            font-weight: 600;
            letter-spacing: -3px;
            line-height: 60px;

            span{
                color: $tertiaryColorBrand;
            }
        }
    }

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

    .side-text{
        transform: rotate(-180deg);
        writing-mode:vertical-lr;
        text-align: center;
        margin-left: 25px;
        font-size: 13px;
    }

    .margin-tb{
        margin: 200px 0;
    }

</style>