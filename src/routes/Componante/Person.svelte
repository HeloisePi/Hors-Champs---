<script>
    export let srcImg;
    export let name;
    export let description;
</script>

<div>
    <img src="{srcImg}" alt="{name}">
    <h3>{name}</h3>
    <p>{description}</p>
</div>

<style>
    h3{
        font-size: 32px;
    }
</style>