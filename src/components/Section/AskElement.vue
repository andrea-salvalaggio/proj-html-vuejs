<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <div class="ask-container secondary-gradient d-flex flex-column align-items-center">
                        <span>Are You Ready?</span>
                        <h2>Start a New Project</h2>
                        <div class="input-group mt-5">
                            <input type="email" class="form-control border-0 rounded-end rounded-pill ps-4 input-email" placeholder="Enter Your Email Address">
                            <button class="btn btn-outline-secondary border-0 rounded-start rounded-pill pe-4 btn-submit " type="button" id="button-addon2">Submit</button>
                        </div>
                    </div>
                    <div class="ask-container primary-gradient">

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../../styles/variables.scss";

    .ask-container{
        color: #ffff;
        padding: 80px;
        border-radius: 20px;

        span{
            font-size: 15px;
            font-weight: 600;
            color: $tertiaryColorText;
        }

        h2{
            font-size: 35px;
            font-weight: 600;
        }
    }

    .secondary-gradient{
        background: linear-gradient(90deg, $primaryColorBg, $secondaryColorBg);
        box-shadow: 0 8px 20px rgba($secondaryColorBg, $alpha: 0.3);
    }

    .input-email{
        font-weight: 600;
        margin-right: 1px;
        padding: 20px;
        background-color: rgba($color: #ffffff, $alpha: 0.1);
    }

    .btn-submit{
        font-weight: 600;
        text-transform: uppercase;
        background-color: rgba($color: #ffffff, $alpha: 0.1);

        &:hover{
            color: black;
            background-color: #ffff;
        }
    }

</style>