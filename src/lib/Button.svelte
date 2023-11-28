<script lang="ts">
    export let variant: string;

    export let href: string;

    function go() {
        window.location.href = href;
    }
</script>

<style>
    .btn-purple {
        color: #fff;
        background-color: #6441a4;
    }

    .btn-purple:hover {
        color: #fff;
        background-color: #482e75;
    }

    .btn-blurple {
        color: #fff;
        background-color: #5865F2;
    }

    .btn-blurple:hover {
        color: #fff;
        background-color: #4752c4;
    }

    .btn-orange {
        color: #fff;
        background-color: #f58025;
    }

    .btn-orange:hover {
        color: #fff;
        background-color: #c2651e;
    }

    .btn-reddit {
        color: #fff;
        background-color: #FF4500;
    }

    .btn-reddit:hover {
        color: #fff;
        background-color: #c43500;
    }

    .btn-youtube {
        color: #fff;
        background-color: #c4302b;
    }

    .btn-youtube:hover {
        color: #fff;
        background-color: #932521;
    }

    .btn {
        color: white;
        font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Oxygen, Ubuntu, Cantarell, Fira Sans, Droid Sans, Helvetica Neue, sans-serif;
        letter-spacing: 1px;
        font-size: 14px;
        font-weight: 600;
        text-align: center;
        text-transform: uppercase;
    }

    .btn-light {
        color: black;
    }
</style>

<button class={`btn btn-${variant} rounded-0 m-0 py-3 px-4`} on:click={go}>
    <slot/>
</button>