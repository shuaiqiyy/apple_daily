<style>
.essay_img {
    top: 5000px;
}

.image_essay_first {
    width: 300px;
    height: 200px;
}

.image_essay_second {
    width: 300px;
    height: 95px;
}
</style>

<template>
    <div class="essay_img">
        <div class="two_grid">
            <div class="two_grid_item">
                <img class="image_essay_first" src="./image/1.jpg">
            </div>
            <div class="two_grid_item">
                <div class="vertical">
                    <div class="upper-vertical">
                        <img class="image_essay_second" src="./image/1.jpg">
                    </div>
                    <div class="lower-vertical">
                        <img class="image_essay_second" src="./image/1.jpg">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>