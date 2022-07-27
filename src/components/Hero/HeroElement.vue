<template>
    <div class="tertiary-bg d-flex align-items-center">
        <div class="container margin-info">
            <div class="row">
                <div class="col-12">
                    <h4>17 years of experience</h4>
                    <h1>Focus on Your Business</h1>
                    <div>
                        <div></div>
                    </div>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Animi mollitia fugit quod error corporis cupiditate fuga cum omnis ducimus numquam? Quibusdam blanditiis vero quis iure repellendus, facere illum tempora facilis.</p>
                    <button>Read more</button>
                    <div>facebook - instagram - youtube - twitter</div>
                </div>
            </div>
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

    .margin-info{
        margin-left: 200px;
    }

</style>