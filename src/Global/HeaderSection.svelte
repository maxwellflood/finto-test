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
        width: 100%;
        height: 100%;
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

</style>