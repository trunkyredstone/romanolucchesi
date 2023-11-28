<style>
    .app {
        font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Oxygen, Ubuntu, Cantarell, Fira Sans, Droid Sans, Helvetica Neue, sans-serif;
        letter-spacing: 1px;
        font-size: 16px;
        font-weight: 200;
        text-align: center;
    }
</style>

<div class="app bg-black text-white h-100 align-items-center h-100">
    <div class={"align-items-center h-100 row mx-0"}>
        <slot/>
        <footer class="pb-3">
            <small>Made on Svelte with {"<3"} © Romano Lucchesi 2021-2023</small>
            <br/>
            <img alt={"favicon"} src={"favicon.ico"}/>
        </footer>
    </div>
</div>