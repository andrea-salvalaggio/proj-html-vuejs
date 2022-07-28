<template>
    <div class="container">
        <div class="row">
            <div class="col-12 margin-t margin-b">
                <div class="partner-container d-flex justify-content-between">
                    <img src="../../assets/img/client-1-2x.png" alt="">
                    <img src="../../assets/img/client-1-2x.png" alt="">
                    <img src="../../assets/img/client-1-2x.png" alt="">
                    <img src="../../assets/img/client-1-2x.png" alt="">
                    <img src="../../assets/img/client-1-2x.png" alt="">
                    <img src="../../assets/img/client-1-2x.png" alt="">
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
            ],
        }
    }

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    // .margin-b{
    //     margin-bottom: 100px 0;
    // }

</style>