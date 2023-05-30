
<template>
    <div class="left-section">
        <div class="rectangle">
            <img class="spotify-logo" src="@/assets/imgs/spotify-logo.png">

            <div class="left-options-top">
                <div class="rectangle-item">
                    <div class="home2">
                        <svg class="fi-ss-home" width="24" height="26" viewBox="0 0 24 26" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <g clip-path="url(#clip0_1_36)">
                                <path
                                    d="M12 15.1663C11.2044 15.1663 10.4413 15.5087 9.87868 16.1182C9.31607 16.7277 9 17.5544 9 18.4163V26.0278H15V18.4163C15 17.5544 14.6839 16.7277 14.1213 16.1182C13.5587 15.5087 12.7956 15.1663 12 15.1663Z"
                                    fill="white"></path>
                                <path
                                    d="M13.338 0.902532C12.9707 0.544422 12.4941 0.346268 12 0.346268C11.5059 0.346268 11.0293 0.544422 10.662 0.902532L0 11.2982V22.5649C0 23.4843 0.337142 24.366 0.937258 25.0162C1.53737 25.6663 2.35131 26.0315 3.2 26.0315H7V18.4168C7 16.9802 7.52678 15.6024 8.46447 14.5866C9.40215 13.5708 10.6739 13.0001 12 13.0001C13.3261 13.0001 14.5979 13.5708 15.5355 14.5866C16.4732 15.6024 17 16.9802 17 18.4168V26.0283H20.8C21.6487 26.0283 22.4626 25.663 23.0627 25.0129C23.6629 24.3628 24 23.481 24 22.5616V11.2949L13.338 0.902532Z"
                                    fill="white"></path>
                            </g>
                            <defs>
                                <clipPath id="clip0_1_36">
                                    <rect width="24" height="26" fill="white"></rect>
                                </clipPath>
                            </defs>
                        </svg>

                        <div class="home3">Home</div>
                    </div>

                </div>

                <div class="search">
                    <div class="fi-rs-search">
                        <svg class="_01-align-center" width="25" height="25" viewBox="0 0 25 25" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M24.9998 23.5867L18.7378 17.3247C20.3644 15.3353 21.1642 12.7968 20.9716 10.2343C20.7791 7.67174 19.609 5.28124 17.7034 3.55723C15.7977 1.83322 13.3024 0.907605 10.7334 0.971837C8.16447 1.03607 5.71848 2.08524 3.9014 3.90233C2.08431 5.71942 1.03514 8.1654 0.970906 10.7344C0.906674 13.3033 1.83229 15.7987 3.5563 17.7043C5.28031 19.6099 7.67081 20.78 10.2333 20.9726C12.7959 21.1651 15.3344 20.3653 17.3238 18.7387L23.5858 25.0007L24.9998 23.5867ZM10.9998 19.0007C9.41753 19.0007 7.87081 18.5315 6.55522 17.6525C5.23963 16.7734 4.21425 15.524 3.60875 14.0622C3.00324 12.6004 2.84482 10.9918 3.1535 9.43999C3.46218 7.88814 4.22411 6.46268 5.34293 5.34386C6.46175 4.22504 7.88721 3.46311 9.43906 3.15443C10.9909 2.84575 12.5994 3.00418 14.0612 3.60968C15.5231 4.21518 16.7725 5.24056 17.6515 6.55615C18.5306 7.87174 18.9998 9.41846 18.9998 11.0007C18.9974 13.1217 18.1538 15.1552 16.654 16.6549C15.1542 18.1547 13.1208 18.9983 10.9998 19.0007Z"
                                fill="white"></path>
                        </svg>
                    </div>

                    <div class="search2">Search</div>
                </div>
            </div>

        </div>
    </div>
</template>

<script lang="ts" setup>
const props = defineProps({
    text: String
})
</script>

<style lang="scss">
.home,
.home * {
    box-sizing: border-box
}

.home {
    background: #fff;
    width: 1920px;
    height: 909px;
    position: relative
}


.left-section {
    position: absolute;
    inset: 0
}

.rectangle {
    background: #000;
    width: 301px;
    height: 100vh;
    position: absolute;
    left: 0;
    top: 1px
}

.left-options-top {
    width: 281px;
    height: 138px;
    position: static;
    margin-top: 24px
}

.rectangle-item {
    background: #282828;
    border-radius: 6px;
    width: 281px;
    height: 50px;
    display: flex;
    margin-left: 10px
}

.home2 {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: start;
    align-items: center
}

.home3 {
    color: #fff;
    text-align: left;
    font: 700 19px 'DM Sans', sans-serif;
    padding-left: 23px
}

.fi-ss-home {
    margin-left: 23px;
    overflow: visible;
    width: 24px;
    height: 26px
}

.search {
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: start;
    align-items: center;
    margin-left: 10px
}

.search2 {
    color: #fff;
    text-align: left;
    font: 700 19px 'DM Sans', sans-serif;
    margin-left: 23px
}

.fi-rs-search {
    margin-left: 23px;
    width: 24px;
    height: 24px
}

._01-align-center {
    overflow: visible
}

.spotify-logo {
    padding-left: 29px;
    padding-top: 32px
}
</style>
