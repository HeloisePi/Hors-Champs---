<script>
    export let title;
    export let videoSrc;
</script>

<div class="video" id="{title}">
    <img src="/images/star.svg" alt="star">
    <h2>{title}</h2>
    <div ><iframe 
        src="{videoSrc}" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen></iframe></div>
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

    img{
        position: absolute;
        width: 4rem;
        transform: translate(-5rem,1rem);
    }
    iframe{
        width: 60vw;
        height: 40vw;
    }
</style>