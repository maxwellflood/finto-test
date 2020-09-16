<script>
    import Button from './Button.svelte'
</script>


<section>

    <div class="text-wrapper">
        <div class="text-block">
            <h1>Digital banking infrastructure</h1>
            <p>Build the financial services of the future with Finto’s cutting-edge API platform and white label banking solutions.</p>
            <Button mode="fill large">Get started</Button>
        </div>
    </div>

    <div class="bg-tex">
        <img class="glass-01" src="assets/vector/glass-dark.svg" alt="">
        <!-- <img class="glass-02" src="assets/vector/glass-dark.svg" alt=""> -->
        <img class="glass-03" src="assets/vector/glass-dark.svg" alt="">
    </div>

</section>


<style>

    section{
        display: block;
        position: relative;
        width: 100%;
        height: 100vh;
        /* background-color: var(--red); */
    }
    .text-wrapper{
        position: relative;
        width: 100%;
        height: 100%;
        z-index: 10;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .text-block{
        max-width: 600px;
        color: var(--white);
        margin: auto;
        text-align: center;
    }

    h1,p{
        padding-bottom: 40px;
    }

    .bg-tex{
        position: absolute;
        top: 0;
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        overflow-x: hidden;
    }

    .glass-01{
        margin-left: 20%;
        transform: translateY(10%);
        width: 28vw;
        max-width: 100%;
    }

    .glass-03{
        transform: translateY(-60%);
        width: 28vmax;
    }

</style>