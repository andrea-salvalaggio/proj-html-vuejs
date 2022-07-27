<template>
    <div class="bg-white margin-tb">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <div class="line-small line-gradient rounded-pill">
                        <div class="line-big line-gradient rounded-pill"></div>
                    </div>
                    <h1 class="">Our recent <span>web design</span> & <br> some examples of <br> past <span>projects</span></h1>
                    <div class="line-small line-gradient rounded-pill">
                        <div class="line-big line-gradient rounded-pill"></div>
                    </div>
                </div>
                <div class="col-6 d-flex align-items-end">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet corporis, dolorem quas doloremque unde numquam voluptas deserunt! Quod similique corporis ut in molestias delectus, praesentium consequuntur impedit doloribus vero soluta.</p>
                </div>

                <CardProjects/>

                <div class="text-center">
                    <button class="button button-primary">Read more</button>
                </div>

                <div class="side-text">
                    <span>17 years of experience helping people for best solutions</span>  
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import CardProjects from '../Card/CardProjects.vue';

export default {

    components: {
        CardProjects,
    },
}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

        h1{
            font-size: 50px;
            font-weight: 600;
            letter-spacing: -3px;
            line-height: 60px;
            margin: 30px 0;
        }

        .margin-tb{
        margin: 200px 0;
        }

        .side-text{
        transform: rotate(-180deg);
        writing-mode:vertical-lr;
        text-align: center;
        margin-left: 25px;
        font-size: 13px;
        position: relative;
        top: -650px;
        right: -30px;
        }

</style>