<template>
    <header>
        <div class="primary-bg">
            <div class="container">
                <div class="row">
                    <div class="col-12 d-flex justify-content-between p-1">
                        <div class="icon-container">
                            <img src="../assets/img/phone-icon-white.png" alt="Phone Icon">
                            <span>(001)88451234 &nbsp &nbsp 88455438</span>
                        </div>
                        <div class="icon-container">
                            <img src="../assets/img/fb-icon-white.png" alt="Facebook Icon">
                            <img src="../assets/img/twitter-icon-white.png" alt="Twitter Icon">
                            <img src="../assets/img/pinterest-icon-white.png" alt="Pinterest Icon">
                        </div>                
                    </div>
                </div>
            </div>
        </div>

        <div class="bg-white">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <nav class="d-flex justify-content-between align-items-center py-4">
                            <div>
                                <img class="w-75" src="../assets/img/cropped-Group-39-2x.png" alt="Company Logo">
                            </div>
                            <div>
                                <ul>
                                    <li v-for="(link, index) in links" :key="index"><a :href="link.url"> {{ link.text }} </a></li>
                                </ul>
                            </div>
                            <div class="icon-container">
                                <button class="button button-primary me-3">Purchase</button>
                                <img src="../assets/img/search-icon-color.png" alt="Search Icon">
                            </div>
                        </nav>
                    </div>
                </div>
            </div>
        </div>

        <HeroElement/>

    </header>
</template>

<script>
import HeroElement from './Hero/HeroElement.vue';

export default {

    components: {
        HeroElement,
    },

    data: function(){
        return{
            links:[
                {
                    text: "Home",
                    url: "#",
                },
                {
                    text: "About",
                    url: "#",
                },
                {
                    text: "Services",
                    url: "#",
                },
                {
                    text: "Showcase",
                    url: "#",
                },
                {
                    text: "Blog",
                    url: "#",
                },
                {
                    text: "Contact",
                    url: "#",
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

    .primary-bg{
        background-color: $primaryColorBg;
    }

    .icon-container{
        img{
            width: 15px;
            margin: 0 10px;
        }
        
        span{
            font-size: 12px;
            color: #ffff;
        }
    }

    ul{
        list-style: none;
        margin: 0;
        padding: 0;

        li{
            display: inline-block;
            padding: 0 15px;
        }

        a{
            font-size: 12px;
            color: black;
            text-transform: uppercase;
            text-decoration: none;

            &:hover{
                font-weight: 600;
            }
        }
    }

    .button{
        width: 150px;
        height: 50px;
        font-size: 12px;
        font-weight: 600;
        color:white;
        text-transform: uppercase;
        border: none;
        border-radius: 50px;
    }

    .button-primary{
        background: linear-gradient(90deg, $secondaryColorBrand, $tertiaryColorBrand);

        &:hover{
            box-shadow: 0 8px 20px rgba($primaryColorBrand, $alpha: 0.5);
        }
    }

</style>