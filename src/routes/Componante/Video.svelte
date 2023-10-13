<script>
    export let title;
    export let videoSrc;
</script>

<div class="video" id="{title}">
    <img src="/images/star.svg" alt="star">
    <h2>{title}</h2>
    <div ><video src="{videoSrc}"></video></div>
</div>

<style>
    .video{
        width: 100vw;
        padding-left: 20vw;
        padding-right: 20vw;
    }
    h2{
        width: 215px;
        margin-bottom: 1rem;
    }

    .video div{
        background-color: #D9D9D9;
        height: 360px;
    }
    img{
        position: absolute;
        width: 4rem;
        transform: translate(-5rem,1rem);
    }
</style>