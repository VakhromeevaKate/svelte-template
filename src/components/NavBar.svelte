<script>
    export let title;
</script>

<div>
    <h1>{title}</h1>
</div>

<style>
    div {
        background-color: pink;
    }

    h1 {
        color: #330000;
        text-transform: uppercase;
        font-size: 4em;
        font-weight: 100;
    }

    @media (min-width: 640px) {
        div {
            max-width: none;
        }
    }
</style>