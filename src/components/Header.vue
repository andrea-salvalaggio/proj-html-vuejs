<template>
    <header class="primary-bg">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex justify-content-between p-1">
                    <div>
                        <img class="icon-topbar" src="../assets/img/phone-icon-white.png" alt="Phone Icon">
                        <span class="phone-info">(001)88451234 &nbsp &nbsp 88455438</span>
                    </div>
                    <div>
                        <img class="icon-topbar" src="../assets/img/fb-icon-white.png" alt="Facebook Icon">
                        <img class="icon-topbar" src="../assets/img/twitter-icon-white.png" alt="Twitter Icon">
                        <img class="icon-topbar" src="../assets/img/pinterest-icon-white.png" alt="Pinterest Icon">
                    </div>                
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../styles/variables.scss";

    // Topbar
    .primary-bg{
        background-color: $primaryColorBg;
    }

    .icon-topbar{
        width: 15px;
        margin: 0 10px;
    }

    .phone-info{
        font-size: 12px;
        color: #ffff;
    }

</style>