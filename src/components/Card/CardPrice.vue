<template>
    <div class="d-flex">
        <div class="chat-container">
            <div class="gradient-container">
                <div class="title-container">
                    <h5>Designing</h5>
                    <div class="subtitle">All Designs</div>
                </div>
                <h4><span>$</span> 13 <span>/Design</span></h4>
            </div>
            <ul>
                <li>Creative Design Enabled</li>
                <li>Vibrant Color Usage</li>
                <li>Eye Catching Design</li>
                <li>Extreme Typography</li>
                <li>Exceptional Design</li>
            </ul>
        </div>
        <div class="chat-container">
            <div id="primary" class="gradient-container">
                <div class="title-container">
                    <h5>Development</h5>
                    <div class="subtitle">WordPress Projects</div>
                </div>
                <h4><span>$</span> 15 <span>/Project</span></h4>
            </div>
            <ul>
                <li>Creative Design Enabled</li>
                <li>Vibrant Color Usage</li>
                <li>Eye Catching Design</li>
                <li>Extreme Typography</li>
                <li>Exceptional Design</li>
            </ul>
        </div>
        <div class="chat-container">
            <div class="gradient-container">
                <div class="title-container">
                    <h5>Seo</h5>
                    <div class="subtitle">Web Products</div>
                </div>
                <h4><span>$</span> 10 <span>/Product</span></h4>
            </div>
            <ul>
                <li>Creative Design Enabled</li>
                <li>Vibrant Color Usage</li>
                <li>Eye Catching Design</li>
                <li>Extreme Typography</li>
                <li>Exceptional Design</li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    #primary{
        background: linear-gradient(90deg, $secondaryColorBrand, $tertiaryColorBrand);
    }

    .chat-container{
        width: calc((100% / 3) - 30px);
        margin: 0 15px;
        text-align: center;
        border-radius: 15px;
        box-shadow: 0 8px 40px rgba($secondaryColorBg, $alpha: 0.1);
    }

    .gradient-container{
        border-radius: 15px 15px 0 0;
        background: linear-gradient(90deg, $primaryColorBg, $secondaryColorBg);
         

        h4{
            margin-top: 40px;
            padding-bottom: 10px;
            color: white;
            font-size: 55px;

            span{
                font-size: 20px;
                vertical-align: middle;
            }
        }
    }

    .title-container{
        background-color: #ffff;
        padding: 20px 0;
        position: relative;
        top: 20px;

        .subtitle{
            font-size: 14px;
            color: $tertiaryColorText;
        }

        h5{
            font-weight: 600;
            text-transform: uppercase;
        }
    }

    ul{
        list-style: none;
        padding: 20px 0;

        li{
            font-size: 14px;
            line-height: 40px;

            &::before{
                content: '\2713';
                color: black;
                margin-right: 10px;
            }
        }
    }

</style>