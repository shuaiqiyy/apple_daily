<style>
.add {
    position: fixed;
    height: 50px;
    bottom: 0;
    left: 0;
    right: 0;
    padding: 10px;
    border-radius: 5%;
    text-align: center;
    background: linear-gradient(rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.2) 100%);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
}

.add_button {
    background: transparent;
    border: none;
}
</style>
<template>
    <div class="add">
        <div class="center">
            <button class="add_button">
                <svg t="1723358065723" class="icon" viewBox="0 0 1024 1024" version="1.1"
                    xmlns="http://www.w3.org/2000/svg" p-id="5285" width="50" height="50">
                    <path
                        d="M512 0C229.376 0 0 229.376 0 512s229.376 512 512 512 512-229.376 512-512S794.624 0 512 0z m238.08 570.88h-179.2v179.2c0 32.768-26.112 58.88-58.88 58.88s-58.88-26.112-58.88-58.88v-179.2h-179.2c-32.768 0-58.88-26.112-58.88-58.88s26.112-58.88 58.88-58.88h179.2v-179.2c0-32.768 26.112-58.88 58.88-58.88s58.88 26.112 58.88 58.88v179.2h179.2c32.768 0 58.88 26.112 58.88 58.88s-26.112 58.88-58.88 58.88z"
                        fill="#5B5791" p-id="5286"></path>
                </svg>
            </button>
        </div>
    </div>
</template>