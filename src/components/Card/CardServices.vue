<template>
    <div class="d-flex flex-wrap">
        <div v-for="(card, index) in cards" :key="index" class="card-container">
            <img :src="card.img" :alt="card.title">
            <h5> {{ card.title }} </h5>
            <p> {{ card.text }} </p>
        </div>
    </div>
</template>

<script>
export default {

    data: function(){
        return{
            cards: [
                {
                    img: require("../../assets/img/speed-icon.svg"),
                    title: "Speed Optimization",
                    text: "Far far away, behind the word mountains, far from the countries Vokalia Separated...",
                },
                {
                    img: require("../../assets/img/cloud-icon.svg"),
                    title: "Cloud Solutions",
                    text: "Far far away, behind the word mountains, far from the countries Vokalia Separated...",
                },
                {
                    img: require("../../assets/img/tablet-icon.svg"),
                    title: "Website Design",
                    text: "Far far away, behind the word mountains, far from the countries Vokalia Separated...",
                },
                {
                    img: require("../../assets/img/alarm-icon.svg"),
                    title: "Online Marketing",
                    text: "Far far away, behind the word mountains, far from the countries Vokalia Separated...",
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    .card-container{
        width: calc((100% / 2) - 30px);
        background-color: #ffff;
        border-radius: 10px;
        padding: 40px;
        margin: 15px;
        box-shadow: 0 0 50px rgba(#0000, $alpha: 0.1);

        h5{
            font-size: 25px;
            letter-spacing: -1px;
            margin: 20px 0;
        }

        p{
            font-size: 13px;
            color: $tertiaryColorText;
            margin: 0;
        }

        &:hover{
            background: linear-gradient(-120deg, $secondaryColorBrand, $tertiaryColorBrand);
            box-shadow: 0 0px 50px rgba($primaryColorBrand, $alpha: 0.5);
            cursor: pointer;

            h5{
                color:white;
            }

            p{
                color:white;
            }

            img{
                filter: contrast(100%) brightness(300%);
            }
        }
    }

</style>