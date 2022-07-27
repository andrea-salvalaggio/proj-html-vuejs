<template>
    <div class="d-flex flex-wrap">
        <div class="card-container">
            icon
            <h5>Speed Optimization</h5>
            <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
        </div>
        <div class="card-container">
            icon
            <h5>Speed Optimization</h5>
            <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
        </div>
        <div class="card-container">
            icon
            <h5>Speed Optimization</h5>
            <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
        </div>
        <div class="card-container">
            icon
            <h5>Speed Optimization</h5>
            <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
        </div>
    </div>
</template>

<script>
export default {

    data: function(){
        return{
            cards: [
                {
                    icon: "",
                    title: "Speed Optimization",
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
        padding: 30px;
        margin: 15px;
        box-shadow: 0 0 50px rgba(#0000, $alpha: 0.1);

        h5{
            margin: 20px 0;
        }

        p{
            font-size: 12px;
            color: $tertiaryColorText;
        }
    }

</style>