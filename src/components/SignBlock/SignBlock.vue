<template>
    <div class="sign">
        <div class="sign__title">Get started now</div>
        <div class="items">
            <div class="item1">
                <div class="item1__title">Connect Git repository</div>
                <div class="item1__text">Select a Git provider to start with an existing project from any Git context.</div>
                <div class="item1__btns">
                    <a href="/" class="item1__btn1">
                        <img src="@/assets/gitlab.svg" alt="gitlab">
                        <div class="btn__text">Continue with GitLab</div>
                    </a>
                    <a href="/" class="item1__btn2">
                        <img src="@/assets/github2.svg" alt="github">
                        <div class="btn__text">Continue with GitHub</div>
                    </a>
                    <a href="/" class="item1__btn3">
                        <img src="@/assets/bucket.svg" alt="bucket">
                        <div class="btn__text">Continue with Bitbucket</div>
                    </a>
                </div>
                <div class="item__text2">Or prefix any GitLab, GitHub or Bitbucket URL with</div>
                <a href="/" class="item__link">gitpod.io/#</a>
            </div>
            <div class="item2">
                <div class="item2__title">Launch an example workspace</div>
                <div class="item2__text">Dive into one of our example workspaces</div>
                <div class="item2__btns">
                    <div class="item2__btn">
                        <img src="@/assets/type.svg" alt="TS">
                        <div class="item2__btn-text1">Node or TypeScript</div>
                        <a href="/" class="item2__link">Launch workspace</a>
                    </div>
                    <div class="item2__btn">
                        <img src="@/assets/python.svg" alt="TS">
                        <div class="item2__btn-text2">Python</div>
                        <a href="/" class="item2__link">Launch workspace</a>
                    </div>
                    <div class="item2__btn">
                        <img src="@/assets/go.svg" alt="TS">
                        <div class="item2__btn-text3">Go</div>
                        <a href="/" class="item2__link">Launch workspace</a>
                    </div>
                    <div class="item2__btn">
                        <img src="@/assets/rust.svg" alt="TS">
                        <div class="item2__btn-text4">Rust</div>
                        <a href="/" class="item2__link">Launch workspace</a>
                    </div>
                    <div class="item2__btn">
                        <img src="@/assets/java.svg" alt="TS">
                        <div class="item2__btn-text5">Java</div>
                        <a href="/" class="item2__link">Launch workspace</a>
                    </div>
                    <div class="item2__btn">
                        <img src="@/assets/svelte.svg" alt="TS">
                        <div class="item2__btn-text6">Svelte</div>
                        <a href="/" class="item2__link">Launch workspace</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import '@/components/SignBlock/SignBlock.scss';
</style>