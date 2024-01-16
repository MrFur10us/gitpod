<template>
    <div class="develop">
        <div class="develop__title">Used by 400,000+ developers.</div>
        <div class="items">
            <swiper :slides-per-view="3" :space-between="50" @swiper="onSwiper" @slideChange="onSlideChange">
                <swiper-slide>
                    <div class="item">
                        <div class="item__top">
                            <div class="item__title">GitPod is incredibly cool.</div>
                            <div class="item__text">In my opinion, this is a big step in open source software contribution.
                                I'm excited to see where we go from here.</div>
                        </div>
                        <div class="item__main">
                            <div class="item__img">
                                <img src="@/assets/ben.png" alt="Ben">
                            </div>
                            <div class="item__right">
                                <div class="item__name">Ben Halpern</div>
                                <div class="item__job">Creator and Co-founder <span>@forem</span> and <span>@ThePracticalDev</span></div>
                            </div>
                        </div>
                    </div>
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                        <div class="item__top">
                            <div class="item__title">Let's say we were overwhelmed how smooth @gitpod workspaces creation &
                                own Docker image for workspaces worked.</div>
                            <div class="item__text">Plus, installing @code extensions from the store and integrating @gitlab
                                CI. That blew my mind entirely, and that is hard ;)</div>
                        </div>
                        <div class="item__main">
                            <div class="item__img">
                                <img src="@/assets/michael.png" alt="Michael">
                            </div>
                            <div class="item__right">
                                <div class="item__name">Michael Friedrich</div>
                                <div class="item__job">Developer Evangelist <span>@GitLab</span></div>
                            </div>
                        </div>
                    </div>
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                        <div class="item__top">
                            <div class="item__title">Look at any PR (pull request) in a full coding environment where you
                                can edit, build, and test the PR code, by just prepending</div>
                            <div class="item__text">"gitpod.io#" In my opinion, this is a big step in open source software
                                contribution.
                                I'm excited to see where we go from here.</div>
                        </div>
                        <div class="item__main">
                            <div class="item__img">
                                <img src="@/assets/julius.png" alt="Julius">
                            </div>
                            <div class="item__right">
                                <div class="item__name">Julius Volz</div>
                                <div class="item__job">Creator <span>@PrometheusIO</span></div>
                            </div>
                        </div>
                    </div>
                </swiper-slide>
                <swiper-slide>
                    <div class="item">
                        <div class="item__top">
                            <div class="item__title">I think I’m in love with @gitpod. It’s such a powerful tool. I’ve
                                learned so much in the past week just from</div>
                            <div class="item__text">stumbling across Github repos that interest me and appending
                                “http://gitpod.io/#” to the URL. A+ tool all around.</div>
                        </div>
                        <div class="item__main">
                            <div class="item__img">
                                <img src="@/assets/david.png" alt="David">
                            </div>
                            <div class="item__right">
                                <div class="item__name">David Ressler</div>
                                <div class="item__job">Engineering Manager</div>
                            </div>
                        </div>
                    </div>
                </swiper-slide>
                ...
            </swiper>
        </div>
        <div class="develop__img">
            <img src="@/assets/logos.png" alt="logos">
        </div>
    </div>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        const onSwiper = (swiper) => {
            console.log(swiper);
        };
        const onSlideChange = () => {
            console.log('slide change');
        };
        return {
            onSwiper,
            onSlideChange,
        };
    },
};
</script>

<style lang="scss" scoped>
@import '@/components/DevelopBlock/DevelopBlock.scss';
</style>