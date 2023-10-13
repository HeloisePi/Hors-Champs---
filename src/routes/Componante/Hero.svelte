<script></script>

<section>
    <h1>A LA POURSUITE DU CHAT</h1>
    <div class="">

    
    <div class="imgDescip">
        <h4>
            Hugo, jeune homme impatient et sanguin, et Jo,
             au caractère plutôt effacé et timide, se retrouvent
              à la recherche du chat perdu de Rachel, la copine
               de Hugo qui l’avait laissé sous sa garde. 
        </h4>
        <div class="titleImg">
                <div class="groupImg">
                    <img src="/images/affiche.png" alt="affiche du film">
                    
                </div>
                
                
        </div>
    </div>
    <h5>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti, 
        ipsam eveniet! Quia ipsa labore pariatur soluta nihil officia dicta 
        necessitatibus. At, molestiae accusantium?
        Adipisci libero vitae fugit maiores quis eveniet?Quasi, inventore. Dolor</h5>
    </div>
</section>

<style>
    section{
        background-color:#BFDFFF ;
        padding-bottom: 5rem;
        
    }
    .imgDescip{
        display: grid;
        grid-template-columns: 1fr 1fr;
    }

    .groupImg{
       text-align: end;
        margin-right: 7rem;
    }

    img{
        width: 21rem;
    }
    
    h1{
        text-align: end;
        margin-right: 7rem;;
        padding-top: 5rem;
        margin-bottom: 1rem;
    }

    h4{
        padding-left: 5vw;
    }
    h5{
        font-size: 12px;
        rotate: -90deg;
        width: 28rem;
        text-align: left;
        display: none;
       
    }

    @media screen and (max-width: 895px) {
        .imgDescip{
        grid-template-columns: 1fr ;
        grid-template-rows: 1fr 2fr;
        justify-items: center;
    }
    .groupImg{
       text-align: end;
        margin-right: 0rem;
    }
    h1{
        text-align: center;
        margin-right: 0rem;
        padding-top: 5rem;
        margin-bottom: 1rem;
    }
    }


</style>