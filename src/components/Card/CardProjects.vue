<template>
        <div class="d-flex flex-wrap container-margin-tb">
            <div v-for="(project, index) in projects" :key="index" class="img-container">
                <img :src="project.img" :alt="project.text">
            </div>
        </div>
</template>

<script>
export default {

    data: function(){
        return{
            projects:[
                {
                    img: require("../../assets/img/ina-soulis-227104-unsplash-1024x1024.jpg"),
                    text: "Flowers",
                },
                {
                    img: require("../../assets/img/sunisa-misa-531163-unsplash-1024x1024.jpg"),
                    text: "Ferris wheel",
                },
                {
                    img: require("../../assets/img/355H-1024x1024.jpg"),
                    text: "Sneakers shoes",
                },
                {
                    img: require("../../assets/img/photo-1448932252197-d19750584e56-1024x1024.jpg"),
                    text: "Work at the office",
                },
                {
                    img: require("../../assets/img/business-competition-PB366D8-1024x1024.jpg"),
                    text: "Origami",
                },
                {
                    img: require("../../assets/img/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg"),
                    text: "Sofa",
                },
                {
                    img: require("../../assets/img/aa9a4539-PQGJ7HU-1024x1024.jpg"),
                    text: "Hot air baloon",
                },
                {
                    img: require("../../assets/img/cody-davis-253928-unsplash-1024x1024.jpg"),
                    text: "Blue lemon",
                },
            ],
        }
    }

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    .img-container{
        width: calc((100% / 4) - 6px);
        margin: 3px;

        img{
            width: 100%;
        }
    }

    .container-margin-tb{
        margin: 100px 0;
    }

</style>