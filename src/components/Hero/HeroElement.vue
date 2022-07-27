<template>
    <div class="tertiary-bg d-flex align-items-center">
        <div class="container-hero">
            <h6>17 years of experience</h6>
            <h1>Focus on Your <span>Business</span></h1>
            <div>
                <div></div>
            </div>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi mollitia fugit quod error corporis cupiditate fuga cum omnis ducimus numquam? Quibusdam blanditiis vero quis iure repellendus, facere illum tempora facilis.</p>
            <button>Read more</button>
            <div>facebook - instagram - youtube - twitter</div>
        </div>
        <div class="hero-bg">
            <img src="../../assets/img/Group-35-2x.png" alt="Business man at work">
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
        width: 6000px;
        height: 800px;
        position: relative;
        left: 300px;

        img{
            width: 100%;
            height: 100%;
            object-fit: cover;
        };
    }

    .container-hero{
        margin-left: 200px;

        h1{
            font-size: 100px;
            font-weight: 800;
            letter-spacing: -7px;
            line-height: 100px;
            margin: 30px 0;

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
    }

</style>