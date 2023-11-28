<script>
    import Button from "$lib/Button.svelte";
</script>

<style>
    .my-face {
        box-shadow: 3px 3px 1px rgb(255, 255, 255);
        border-radius: 300px;
    }

    h1 {
        text-transform: uppercase;
        font-weight: 600;
        font-size: 32px;
        letter-spacing: 3px;
        color: white;
    }
</style>


<div>
    <h1>Romano Lucchesi</h1>
    <img alt={"me"} class={"my-3 my-face"} height={300} src={"me.jpg"}/>
</div>
<div>
    <p>
        I'm a part <b><span class={"text-success"}>it</span>ali<span class={"text-danger"}>an</span></b> student /
        programmer from the UK, focused on devops and full stack development
    </p>

    <Button href={"https://www.youtube.com/channel/UCnrxILtJAgXZeNFUqPrmd7A"} variant={"danger"}>
        <i class="bi bi-youtube"/>
    </Button>
    <Button href={"https://www.reddit.com/user/trunkyredstone"} variant={"reddit"}>
        <i class="bi bi-reddit"/>
    </Button>
    <Button href={"https://stackoverflow.com/users/14927628/trunky"} variant={"orange"}>
        <i class="bi bi-stack-overflow"/>
    </Button>
    <Button href={"/portfolio"} variant={"warning"}>
        Portfolio
    </Button>
    <Button href={"https://open.spotify.com/user/trunkyredstone?si=8680b6f0953d4cb5"} variant={"success"}>
        <i class="bi bi-spotify"/>
    </Button>
    <Button href={"https://twitter.com/imtrunky"} variant={"info"}>
        <i class="bi bi-twitter"/>
    </Button>
    <Button href={"https://twitch.tv/imtrunky"} variant={"purple"}>
        <i class="bi bi-twitch"/>
    </Button>
    <br/> <br/>
    <Button href={"mailto:me@romanolucchesi.com"} variant={"info"}>
        Email me
    </Button>
</div>
