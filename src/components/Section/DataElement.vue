<template>
    <div class="tertiary-bg">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex justify-content-start margin-tb">

                    <!-- Image box gradient -->
                    <div class="data-container">
                        <div class="overlay-gradient">
                            <img src="../../assets/img/person-with-long-curly-hair-PZ99QM2-2x.jpg" alt="Girl in the studio">
                        </div>
                    </div>

                    <!-- Text box -->
                    <div class="info-container d-flex flex-column justify-content-center margin-tb">
                        <h1 class="mb-4">We <span>Love</span> What<br>We Do</h1>
                        <div class="line-small line-gradient rounded-pill">
                            <div class="line-big line-gradient rounded-pill"></div>
                        </div>
                        <p class="my-4">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aut laboriosam architecto soluta distinctio et ipsum, vel sit, fugit vitae officia maiores recusandae veritatis. Obcaecati, sint temporibus consectetur aut aliquid a.</p>
                        <ul class="p-0">
                            <li>far far wawy, behind the word mountains</li>
                            <li>large language ocean</li>
                            <li>far from the oustries Vokalia and Consonantia</li>
                        </ul>
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
        position: relative;
    }

    .data-container{
        width: 800px;
        height: 600px;
        box-shadow: 0 8px 40px rgba($primaryColorBrand, $alpha: 0.2);

        img{
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 15px;
        }
    }

    .info-container{
        width: 800px;
        height: 600px;
        padding: 80px;
        border-radius: 15px;
        background-color: #ffff;
        box-shadow: 0 8px 40px rgba($secondaryColorBg, $alpha: 0.2);
        position: absolute;
        top: 80px;
        right: 250px;

        h1{
            font-size: 50px;
            font-weight: 600;
            letter-spacing: -3px;
            line-height: 60px;

            span{
                color: $tertiaryColorBrand;
            }
        }

        ul{
            list-style: none;

            li{
                line-height: 30px;

                &::before{
                    content: '\2713';
                    color: $tertiaryColorBrand;
                    margin-right: 10px;
                }
            }
        }

    }

    .overlay-gradient{
        width: 800px;
        height: 600px;
        position: relative;

        &::after{
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            border-radius: 15px;
            background: linear-gradient(-120deg, $secondaryColorBrand, $tertiaryColorBrand);
            opacity: 0.9;
        }
    }

    .margin-tb{
        margin: 200px 0;
    }

</style>