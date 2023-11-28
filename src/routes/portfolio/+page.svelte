<script>
    import Button from "$lib/Button.svelte";
</script>

<style>
    h1 {
        text-transform: uppercase;
        font-weight: 600;
        font-size: 32px;
        letter-spacing: 3px;
        color: white;
    }

    h4 {
        text-transform: uppercase;
        font-weight: 600;
        letter-spacing: 3px;
        color: white;
    }
</style>

<h1 class={"pt-5"}>Portfolio</h1>

<div class="row mx-0 mb-3">
    <div class="col">
        <Button href={"/"} variant={"light"}>Go Back</Button>
    </div>
</div>

<hr/>

<div class="row mx-0 mb-3">
    <div class="col">
        <img alt="mrhsolutions.co.uk" class="w-100" src="mrh.png"/>
    </div>
    <div class="col">
        <h4>MRH Solutions</h4>
        <p>
            A small website created for MRH Solutions LTD with React and Bootstrap. My first project,
            comprises of a simple homepage with rotating gallery of pictures, and a booking page that
            uses tradify.
        </p>
        <Button href={"https://mrhsolutions.co.uk"} variant={"light"}>
            Go to site
        </Button>
    </div>
</div>

<hr/>

<div class="row mx-0 mb-3">
    <div class="col">
        <h4>Romano Lucchesi</h4>
        <p>
            This website, originally programmed in react and rewritten for svelte. Now hosted on cloudflare pages.
            Contains my portfolio and contact information.
        </p>
    </div>
    <div class="col">
        <img alt="romanolucchesi.com" class="w-100" src="romanolucchesi.png"/>
    </div>
</div>

<hr/>

<div class="row mx-0 mb-3">
    <div class="col">
        <img alt="punchandpour.co.uk" class="w-100" src="punchandpour.png"/>
    </div>
    <div class="col">
        <h4>
            Punch and Pour
        </h4>
        <p>
            Recreated from an old PHP-based version of the site using React and Bootstrap. Made in about
            a week due to time constraints. Lightweight, snappy and responsive - all a website needs to
            be.
        </p>
        <Button href={"https://punchandpour.co.uk"} variant={"light"}>
            Go to site
        </Button>
    </div>
</div>

<hr/>
