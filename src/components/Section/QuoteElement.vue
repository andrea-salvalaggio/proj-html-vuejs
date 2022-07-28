<template>
    <div class="image-bg">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="quote-container">

                        <!-- Quote text -->
                        <img class="quote-icon" src="../../assets/img/quote-icon.svg" alt="Quote Icon">
                        <p class="text-center mt-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod fugit ex illum sequi qui deleniti quidem sunt quisquam repellat, quis enim! Laborum totam voluptatibus obcaecati dolores commodi? Molestias, sint cum?</p>

                        <!-- Full image bg -->
                        <div class="img-container mt-5">
                            <img src="../../assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
                        </div>

                        <!-- Info client -->
                        <h6>Lissa Durbin</h6>
                        <div class="type">Client</div>
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

    .image-bg{
        background-image: url("../../assets/img/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg");
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        padding: 200px 0;
        position: relative;
        z-index: 1;

        &::after{
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba($color: rgba(50, 50, 50, 0), $alpha: 0.9);
            z-index: -1;
        }
    }

    .quote-container{
        display: flex;
        flex-direction: column;
        align-items: center;

        .quote-icon{
            width: 50px;
        }

        .img-container{
            width: 90px;
            height: 90px;

            img{
                width: 100%;
                height: 100%;
                object-fit: cover;
                border-radius: 50%;
            }
        }

        .type{
            font-size: 18px;
            margin-top: -5px;
            color: white;
        }

        p{
            font-size: 24px;
            font-style: italic;
            color:white;
        }

        h6{
            font-size: 22px;
            font-weight: 600;
            text-transform: uppercase;
            margin-top: 25px;
            color: $tertiaryColorBrand;
        }
    }


</style>