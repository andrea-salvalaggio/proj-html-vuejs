<template>
    <div class="tertiary-bg">
        <div class="d-flex align-items-center">
            <div class="d-flex">
                <div class="img-container">
                    <img src="../../assets/img/busy-architect-PYVKWM4-1024x872.jpg" alt="Architect at work">
                    <img src="../../assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="Business woman at work">
                </div>
            </div>
            <div class="container margin-tb">
                <div class="row">
                    <div class="col-10">
                        <div class="services-container">
                            <h1 class="mb-5">learn more <br> about our <br><span>mission</span></h1>
                            <div class="line-small line-gradient rounded-pill">
                                <div class="line-big line-gradient rounded-pill"></div>
                            </div>
                            <p class="mb-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum reiciendis alias totam consequatur magni minus officiis vero distinctio, quos molestias iste, quidem nihil porro maiores expedita, placeat praesentium ipsam ad.</p>
                            <button class="button button-primary mt-5">View all</button>
                        </div>
                    </div>
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
    }

    .services-container{
        margin-left: 300px;

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

    .img-container{
        width: 700px;
        height: 600px;
        position: relative;

        img{
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 0 30px 0 0;
            background: linear-gradient(90deg, $secondaryColorBrand, $tertiaryColorBrand);
        }

        img:nth-child(2){
            position: absolute;
            top: 80px;
            left: 200px;
            border-radius: 10px;
            box-shadow: 0 8px 40px rgba($secondaryColorBg, $alpha: 0.2);
        }
    }

    .margin-tb{
        margin: 200px 0;
    }

</style>