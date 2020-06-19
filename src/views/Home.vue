<template>
    <div class="app">
        <div class="container">
            <div class="slider">
            </div>
        </div>
        <div class="container">
        <div class="hed_main">
            <h1><em>Stay at Resort Name Here</em></h1>
        </div>
        <ul class="dash-list">
            <div class="columns">
                <div class="column is-one-third">
                    <div class="box">
                        <li>
                            <img src="../assets/bed.jpg">
                        </li>
                    <div class="content">
                       <p>Luxurious Bed Room</p>
                    </div>
                    </div>
                </div>
                <div class="column is-one-third">
                    <div class="box">
                        <li>
                            <img src="../assets/hall.jpg">
                        </li>
                    <div class="content">
                       <p>Luxurious Living Room</p>
                    </div>
                    </div>
                </div>
                <div class="column is-one-third">
                    <div class="box">
                        <li>
                            <img src="../assets/suit.jpg">
                        </li>
                    <div class="content">
                       <p>Luxurious Suit Room</p>
                    </div>
                    </div>
                </div>
            </div>
            <div class="columns">
                <div class="column is-one-third">
                    <div class="box">
                        <li>
                            <img src="../assets/out.jpg">
                        </li>
                    <div class="content">
                       <p>Swimming Pool</p>
                    </div>
                    </div>
                </div>
                <div class="column is-one-third">
                    <div class="box">
                        <li>
                            <img src="../assets/swim.jpg">
                        </li>
                    <div class="content">
                       <p>Indoor Swimming Area</p>
                    </div>
                    </div>
                </div>
                <div class="column is-one-third">
                    <div class="box">
                        <li>
                            <img src="../assets/green.jpg">
                        </li>
                    <div class="content">
                       <p>Beautiful Outside View</p>
                    </div>
                    </div>
                </div>
            </div>
        </ul>
        </div>
        <div class="container">
            <div class="hed_main">
                <h1><em>Our Packages</em></h1>
            </div>
            <div class="columns">
                <div class="column is-half">
                    <div class="card">
                        <img src="../assets/stay.jpg" alt="" srcset="">
                        <p class="line">Staying Packages</p>
                    </div>
                </div>
                <div class="column is-half">
                    <div class="card">
                        <img src="../assets/function.jpg" alt="" srcset="">
                        <p class="line">Ceremony Packages</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
.slider{
    width: 100vw !important;
    height: 80vh !important;
    background: url(../assets/1.jpg);
    margin-left: -9%;
    animation: slide 10s infinite;
}
@keyframes slide{
    25%{
    background: url(../assets/1.jpg);
    }
    50%{
    background: url(../assets/2.jpg);
    }
    75%{
    background: url(../assets/3.jpg);
    }
    100%{
    background: url(../assets/4.jpg);
    }
}
.hed_main {
    margin: 30px 0;
    padding: 15px 0;
    position: relative;
    margin: auto;
    max-width: 600px;
    text-align: center;
    overflow: hidden;
}
.hed_main:before {
    position: absolute;
    left: 0;
    right: 0;
    content: '';
    width: 100%;
    height: 1px;
    background-color: #999;
    top: 50%;
    z-index: 0
}
.hed_main h1 {
    margin: 0;
    text-align: center;
    font-family: 20px;
    font-family: "vinchand";
    background-color: #fff;
    padding: 0 20px;
    position: relative;
    z-index: 1;
    display: inline-block;
    color: #67A13D;
}
.dash-list{
    margin: 0 -8px;
    padding: 0;
    list-style: none;
    overflow: hidden;
}
.line{
    position: absolute;
    left: 0;
    bottom: 0;
    right: 0;
    padding: 15px 0;
    text-align: center;
    color: #fff;
    margin: 0;
    transition: all linear 0.2s;
    background-color: rgba(0,0,0,0.8);
}
.footer {
    width: 100vw;
    margin-left: -9%;
    margin-bottom: -3%;
    padding:  9px 15px;
    -moz-background-color: rgba(0,0,0,0.8);
    -ms-background-color: rgba(0,0,0,0.8);
    -o-background-color: rgba(0,0,0,0.8);
    -webkit-background-color: rgba(0,0,0,0.8);
    background-color: rgba(0,0,0,0.8);
}
</style>

<script>
export default {
};
</script>
