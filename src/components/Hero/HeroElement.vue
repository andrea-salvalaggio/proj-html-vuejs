<template>
    <div class="tertiary-bg d-flex align-items-center">
        <div class="container-hero">
            <h6>17 years of experience</h6>
            <h1>Focus on Your <span>Business</span></h1>
            <div class="line-small line-gradient rounded-pill">
                <div class="line-big line-gradient rounded-pill"></div>
            </div>
            <p class="mb-0">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Animi obcaecati assumenda, hic illum qui dicta nam, dolor magnam beatae dolore nesciunt mollitia aut necessitatibus delectus recusandae ipsum, consequatur architecto quis.</p>
            <button class="button-secondary">Read more</button>
            <div class="social-info">facebook &nbsp-&nbsp instagram &nbsp-&nbsp youtube &nbsp-&nbsp twitter</div>
        </div>
        <div class="col-7">
            <div class="hero-bg">
                <img src="../../assets/img/Group-35-2x.png" alt="Business man at work">
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

    .hero-bg{
        width: 100%;
        height: 800px;

        img{
            width: 100%;
            height: 100%;
            object-fit: none;
            object-position: left;
        };
    }

    .container-hero{
        margin-left: 200px;

        h1{
            font-size: 90px;
            font-weight: 800;
            letter-spacing: -7px;
            line-height: 100px;
            margin: 20px 0;

            span{
                color: $tertiaryColorBrand;
            }
        }

        h6{
            color: $primaryColorBrand;
            text-transform: uppercase;
            letter-spacing: 5px;
            font-weight: 600;
        }

        p{
            margin-top: 40px;
        }

        button{
            width: 150px;
            height: 50px;
            font-size: 12px;
            font-weight: 600;
            color:white;
            text-transform: uppercase;
            border: none;
            border-radius: 50px;
            margin: 40px 0;
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

    .button-secondary{
        background: linear-gradient(90deg, $primaryColorBg, $secondaryColorBg);

        &:hover{
            box-shadow: 0 8px 20px rgba($secondaryColorBg, $alpha: 0.2);
        }
    }

    .social-info{
        font-size: 15px;
        font-weight: 600;
        text-transform: uppercase;

    }

</style>