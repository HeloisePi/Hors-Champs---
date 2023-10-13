<script>
</script>

<header>
    <a href="#COURT MÉTRAGE"><h5>Court-métrage</h5></a>
    <a href="#credit"><h5>Crédit</h5></a>
    <a href="#inspiration"><h5>Inspiration</h5></a>
    <a href="#Making Of"><h5>Making of</h5></a>
</header>

<style>
    header{
        display: flex;
        width: 100vw;
        height: 3rem;
        justify-content: end;
        align-items: center;
        gap: 2rem;
        position: fixed;
        top: 0;
        z-index: 2;
        padding-right: 1rem;
        background-color:#8FBDEB ;
    }
    h5{
        cursor: pointer;
    }
    h5:hover{
        text-decoration: underline;
    }
    @media screen and (max-width: 450px) {
        h5{
            font-size: 12px;
        }
        header{
        gap: 1rem;
        }
    }
</style>
