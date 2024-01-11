<script lang="ts">
    let year = new Date().getFullYear();
</script>

<style>
    .app {
        font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Oxygen, Ubuntu, Cantarell, Fira Sans, Droid Sans, Helvetica Neue, sans-serif;
        letter-spacing: 1px;
        font-size: 16px;
        font-weight: 200;
        text-align: center;
    }

    a {
        text-decoration: underline;
        color: white;
    }
</style>

<div class="app bg-black text-white h-100 align-items-center h-100">
    <div class={"align-items-center h-100 row mx-0"}>
        <slot/>
        <footer class="pb-3">
            <small>
                Made on Svelte with {"<3"}
                • <a href="https://status.romanolucchesi.com">Service Status</a>
                • <a href="https://access.romanolucchesi.com">Access</a>
                • <a href="https://email.atomicvr.co.uk">Email</a>
                • © Romano Lucchesi 2021-{year}
            </small>
            <br/>
            <img alt={"favicon"} src={"favicon.ico"}/>
        </footer>
    </div>
</div>