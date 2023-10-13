<script></script>
<section id="inspiration">


<h2>Inspiration</h2>
<h3>COLORIMÉTRIE</h3>
<div class="">
    <img src="/images/moodBoard.webp" alt="MoodBoard">
    <img class="star" src="/images/star2.svg" alt="star">
    <p>À la poursuite du chat, est inspiré des films de Wes Anderson,
         en terme de colorimétrie. Nous voulions des couleurs vives pour
          faire ressortir nos plans et avoir un aspect visuel esthétique.
         Nos couleurs principales sont le bleu et le jaune. </p>
</div>
<div class="images">
    <div></div>
    <div></div>
    <div></div>
</div>
</section>
<style>
    h2{
        margin-left: 10vw;
    }
    h3{
        font-size: 17px;
        transform: translateY(-0.2rem);
        margin-left: 10vw;
        margin-bottom: 1rem;
    }

    div{
        width: 100vw;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    div img{
        width: 32rem;
        margin-bottom: 2rem;
    }

    p{
        width: 45rem;
        margin-bottom: 5rem;
    }

    .images{
        display: flex;
        flex-direction: row;
        gap: 1rem;
    }
    .images div{
        background-color:#D9D9D9;
        width: 328px;
        height: 180px;
    }

    .star{
        position: absolute;
        z-index: -1;
        transform: translate(-1rem,-26rem);
        width: 8rem;
        rotate: 56deg;
    }
    @media screen and (max-width: 600px) {
        div img{
        width: 90vw;
    }
        
    }
    @media screen and (max-width: 873px) {
        .star{
            transform: translate(-13rem,-19rem);
            width: 5rem;
        }
        p{
            width: 80vw;
        }
        .images{
        flex-direction: column;

    }
    }

</style>