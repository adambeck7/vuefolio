<template>
    <div class="wrapper">
        <div class="page-header clear-filter">
            <parallax class="page-header-image" style="background-color:#ffec4f">
            </parallax>
            <div class="container">
                <div class="content-center brand">
                    <img class="n-logo" src="img/adam.co.png" alt="Adam Beck CO Logo">
                    <h1 class="h1-seo tracking-in-expand">Adam Beck</h1>

                </div>
            </div>
        </div>
        <div class="section section-about-us">
            <div class="container">
                <div class="row">
                    <div class="col-md-8 ml-auto mr-auto text-center">
                        <h2 class="title">Who am I?</h2>
                        <h5 class="description">I'm a software developer, teacher, father and life-long learner. I'm
                            passionate about teaching others and I revel in the opportunity to learn something new. I'm
                            dedicated to making a difference in the school system and community. I'm ready and excited
                            to be your new
                            Communications and Web Manager.</h5>
                    </div>
                </div>
                <div class="separator separator-primary"></div>
                <div class="section-story-overview">
                    <div class="row">
                        <div class="col-md-6">
                            <div id="climaHover" class="image-container image-left">
                                <a class="image hover2" href="https://mysterious-escarpment-94857.herokuapp.com/"
                                    target="_blank">
                                    <div class="image-container image-left image hover2" style="background-image: url('img/climascience.png')">
                                    </div>
                                    <div class="middle">
                                        <div class="text">
                                            ClimaScience is a weather app built in Vue. It provides not only the
                                            current forecast for your
                                            location but beautiful visualizations of future and historical data using
                                            Chart.js as well.
                                        </div>
                                    </div>
                                </a>
                                <!-- First image on the left side -->
                                <p class="blockquote quote-margin">"...In him, there is a fair and genuine concern
                                    for
                                    students,
                                    academics, community and ‘what is right’. His sense of empathy – combined with
                                    his
                                    capacity for innovative thinking – will undoubtedly lead him to creating change
                                    in
                                    our community and beyond."
                                    <br>
                                    <br>
                                    <small>-Amanda Reidenbaugh
                                        Mentor</small>
                                </p>

                            </div>
                            <!-- Second image on the left side of the article -->
                            <div class="image-container candid-margin" style="margin-top: 38em;margin-left:.1em; background-image: url('img/candid.png')">
                                <a href="http://candidcolorado.us/portfolio.html" target="blank" class="fill-div"></a>
                            </div>
                        </div>
                        <div class="col-md-5">
                            <!-- <div class="image-container image-right"> -->
                            <a class="" href="https://mysterious-escarpment-94857.herokuapp.com/" target="_blank">
                                <div id="bikeFinder" class="image hover2 image-container image-right" style="background-image: url('img/bike-finder2.png')">

                                    <div class="middle">
                                        <div class="text">
                                            ClimaScience is a weather app built in Vue. It provides not only the
                                            current forecast for your
                                            location but beautiful visualizations of future and historical data using
                                            Chart.js as well.
                                        </div>
                                    </div>
                                </div>
                            </a>
                            <!-- </div> -->
                            <h3>Portfolio</h3>
                            <p class="hover-margin">Hover over any of the images to get a brief description of the
                                project. Click to
                                navigate to the deployed site but please be patient as they're on Heroku's free tier
                                and may take a moment to spin up.
                            </p>
                            <p>
                                Aside from these fun side projects I've helped develop two mobile apps which have over
                                10,000 downloads and 4+ stars in the Google Play Store. I currently develop and
                                maintain
                                everything from simple Wordpress sites to complex custom applications in PHP and
                                Javascript.
                            </p>
                            <p>
                                In the school system I was part of an adminstration tasked with opening a new
                                blended-learning school
                                for at-risk students. I oversaw and managed the online curriculum and piloted the
                                roll-out of Google Apps for Education at our school and later, district wide.
                            </p>
                            <p>
                                Candid Colorado is a side project for my photography. Feel free to check it out to see
                                some of my work.
                            </p>

                        </div>
                    </div>
                </div>
            </div>
        </div>
        <signup-form></signup-form>
    </div>
</template>
<style>
    .scale-in-hor-center {
        -webkit-animation: scale-in-hor-center 0.8s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
        animation: scale-in-hor-center 0.8s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
    }

    .tracking-in-expand {
        -webkit-animation: tracking-in-expand 1.5s cubic-bezier(0.215, 0.610, 0.355, 1.000) 1s both;
        animation: tracking-in-expand 1.5s cubic-bezier(0.215, 0.610, 0.355, 1.000) 1s both;
    }

    /* ----------------------------------------------
 * Generated by Animista on 2018-9-26 14:28:15
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

    /**
 * ----------------------------------------
 * animation scale-in-hor-center
 * ----------------------------------------
 */
    @-webkit-keyframes scale-in-hor-center {
        0% {
            -webkit-transform: scaleX(0);
            transform: scaleX(0);
            opacity: 1;
        }

        100% {
            -webkit-transform: scaleX(1);
            transform: scaleX(1);
            opacity: 1;
        }
    }

    @keyframes scale-in-hor-center {
        0% {
            -webkit-transform: scaleX(0);
            transform: scaleX(0);
            opacity: 1;
        }

        100% {
            -webkit-transform: scaleX(1);
            transform: scaleX(1);
            opacity: 1;
        }
    }

    /* ----------------------------------------------
 * Generated by Animista on 2018-9-26 17:22:31
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

    /**
 * ----------------------------------------
 * animation tracking-in-expand
 * ----------------------------------------
 */
    @-webkit-keyframes tracking-in-expand {
        0% {
            letter-spacing: -0.5em;
            opacity: 0;
        }

        40% {
            opacity: 0.6;
        }

        100% {
            opacity: 1;
        }
    }

    @keyframes tracking-in-expand {
        0% {
            letter-spacing: -0.5em;
            opacity: 0;
        }

        40% {
            opacity: 0.6;
        }

        100% {
            opacity: 1;
        }
    }
</style>
<script>
    document.addEventListener("DOMContentLoaded", function (event) {
        var hoverFix = document.getElementById("climaHover");
        hoverFix.onmouseover = function () {
            document.getElementById("bikeFinder").style.visibility = "hidden"
        }
        hoverFix.onmouseout = function () {
            document.getElementById("bikeFinder").style.visibility = "visible"
        }
        var bikeFix = document.getElementById("bikeFinder");
        bikeFix.onmouseover = function () {
            bikeFix.style.backgroundImage = "linear-gradient(rgba(255, 255, 255, 0.9), rgba(255, 255, 255, 0.9)), url('img/bike-finder2.png')"
            // bikeFix.style.background = "opacity: .1"
        }
        bikeFix.onmouseout = function () {
            bikeFix.style.backgroundImage = "url('img/bike-finder2.png')"
        }
    });

    import { Parallax } from '@/components';
    import BasicElements from './components/BasicElementsSection';
    import Navigation from './components/Navigation';
    import TabsSection from './components/Tabs';
    import ProgressPagination from './components/ProgressPagination';
    import Notifications from './components/Notifications';
    import Typography from './components/Typography';
    import JavascriptComponents from './components/JavascriptComponents';
    import CarouselSection from './components/CarouselSection';
    import NucleoIconsSection from './components/NucleoIconsSection';
    import SignupForm from './components/SignupForm';
    import ExamplesSection from './components/ExamplesSection';
    import DownloadSection from './components/DownloadSection';

    export default {
        name: 'index',
        bodyClass: 'index-page',
        components: {
            Parallax,
            BasicElements,
            Navigation,
            TabsSection,
            ProgressPagination,
            Notifications,
            Typography,
            JavascriptComponents,
            CarouselSection,
            NucleoIconsSection,
            SignupForm,
            ExamplesSection,
            DownloadSection
        }
    };
</script>
<style>
    .bike-margin {
        margin-top: 2rem;
    }

    .candid-margin {
        margin-left: .1rem;
        margin-top: 39em
    }

    .hover-margin {
        margin-top: 2rem
    }

    .quote-margin {
        margin-top: 8.5em
    }

    .middle {
        transition: .5s ease;
        opacity: 0;
        position: absolute;
        top: 45%;
        left: 50%;
        transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
        text-align: center;
    }

    .hover2:hover .image {
        opacity: .1;
        /* z-index: 999999999 !important; */
    }

    .hover2:hover .middle {
        opacity: 1;
    }

    .hover2:active .image {
        opacity: .1;
        /* z-index: 999999999 !important; */
    }

    .section-story-overview.image-container.image-left:hover {
        z-index: 99999;
    }

    .hover2:active .middle {
        opacity: 1;
    }

    .text {
        /* background-color: #4CAF50; */
        color: #363636 !important;
        font-size: 15px;
        /* padding: 5px 5px; */
        z-index: 999999 !important;
    }

    .text {
        /* background-color: #4CAF50; */
        color: #428bca;
        font-size: 15px;
        /* padding: 5px 5px; */
    }

    a.fill-div {
        display: block;
        height: 100%;
        width: 100%;
        text-decoration: none;
    }
</style>