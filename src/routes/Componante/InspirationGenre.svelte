<script></script>
<section>
<h2>Inspiration</h2>
<h3>LE GENRE</h3>
<div class="movie">
    <div class="part1">
        <img src="/images/affiche1.png" alt="Very Bad Trip">
        <p>Very Bad Trip</p>
        <img src="/images/affiche2.png" alt="Little Miss Sunshine">
        <p>Little Miss Sunshine</p>
        <img src="/images/affiche3.png" alt="Dumb and Dumber">
        <p>Dumb and Dumber</p>
    </div>
    <div class="part2">
        <img src="/images/affiche4.png" alt="Harold & Kumar">
        <p>Harold & Kumar</p>
        <img src="/images/affiche5.png" alt="Midnight Run">
        <p>Midnight Run</p>
    </div>
    <div class="part3">
        <img src="/images/affiche6.png" alt="The blues Brothers">
        <p>The blues Brothers</p>
        <img src="/images/affiche7.png" alt="21 jump street">
        <p>21 jump street</p>
    </div>

</div>
<p class="description">Pour réaliser notre court métrage, nous avons tout d’abord visionner plusieurs films sur dans le genre Buddy Comedy Road Trip afin de pouvoir repérer les codes utilisés, l’humour, le duo iconique pour les représenter au mieux dans À la poursuite du chat.</p>
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

    img{
        width: 20vw;
    }

    .movie{
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 2rem;
        margin-bottom: 5rem;
    }

    .description{
        width: 45rem;
        margin: auto;
    }

    @media screen and (max-width: 970px) {
        .movie{
            flex-direction: column;
    }
        img{
            width: 30vw;
        }
        
    }

    @media screen and (max-width: 758px) {
        .description{
            width: 80vw;
        }
    }
</style>