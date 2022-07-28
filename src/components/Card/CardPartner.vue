<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex justify-content-between margin-t margin-b">
                <div v-for="(partner, index) in partners" :key="index" class="partner-container">
                    <img :src="partner.url" :alt="partner.title">
                </div>
            </div>
        </div>
        
    </div>
</template>

<script>
export default {

    data: function(){
        return{
            partners: [
                {
                    url: require('../../assets/img/client-1-2x.png'),
                    title: 'Avant Garde',
                },
                {
                    url: require('../../assets/img/client-9-2x.png'),
                    title: 'FastLane',
                },
                {
                    url: require('../../assets/img/client-7-2x.png'),
                    title: 'Ron Jones',
                },
                {
                    url: require('../../assets/img/client-3-2x.png'),
                    title: 'Chippy',
                },
                {
                    url: require('../../assets/img/client-4-2x.png'),
                    title: 'Bulls Eye',
                },
                {
                    url: require('../../assets/img/client-5-2x.png'),
                    title: 'Mighty Furnitures',
                },
            ],
        }
    }

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    .partner-container{
        width: 120px;
        height: 60px;

        img{
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
    }

</style>