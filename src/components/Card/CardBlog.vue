<template>
    <div class="col-12 d-flex mt-5 position-relative"> 
        <div v-for="(image, index) in images" :key="index" class="blog-container d-flex justify-content-center">
            <div class="image-container">
                <img :src="image.url" :alt="image.name">
            </div>
            <div v-for="(blog, index) in blogs" :key="index" class="text-container d-flex flex-column justify-content-center p-4">
                <span> {{ blog.date }} </span>
                <h4 class="m-0"> {{ blog.title }} </h4>
            </div>
        </div>
    </div>
</template>

<script>
export default {

    data: function(){
        return{
            images:[
                {
                    url: require('../../assets/img/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg'),
                    name: 'Woman at the office',
                },
                {
                    url: require('../../assets/img/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg'),
                    name: 'Rest man at the office',
                },
                {
                    url: require('../../assets/img/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg'),
                    name: 'Minimal office',
                },
            ],

            blogs:[
                {
                    date: 'May 24, 2018 · by Alex',
                    title: 'Marketing Ideas',
                },
                {
                    date: 'May 24, 2018 · by Alex',
                    title: 'Rest During Working Hours',
                },
                {
                    date: 'May 24, 2018 · by Alex',
                    title: 'Develop Your Startup Idea',
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";


    .blog-container{
        width: calc((100% / 3) - 20px);
        margin: 0 10px;
        position: relative;
    }

    .image-container{
        width: 500px;
        height: 350px;
        border-radius: 8px;
        box-shadow: 0 0 40px rgba($secondaryColorBg, $alpha: 0.2);

        img{
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 8px;
        }
    }

    .text-container{
        width: 350px;
        height: 100px;
        background-color: #ffff;
        box-shadow: 0 0 40px rgba($secondaryColorBg, $alpha: 0.1);
        position: absolute;
        bottom: -50px;
        border-radius: 5px;

        span{
            font-size: 13px;
            color: $tertiaryColorText;
        }

        h4{
            font-weight: 600;
            letter-spacing: -1.5px;

            &::before{
                content: '\2022';
                font-size: 30px;
                padding-right: 5px;
                vertical-align: middle;
                color: $tertiaryColorBrand;
            }
        }
    }



</style>