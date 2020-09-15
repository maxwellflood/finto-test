<script>
    import Button from './Button.svelte'
</script>


<nav>
    <div class="nav-wrapper">
        <div class="image-wrapper">
            <img src="assets/vector/logo.svg" alt="">
        </div>
        <div class="nav-menu">
            <button>API Platform</button>
            <button>Banking</button>
            <button>Cards</button>
            <button>Developers</button>
        </div>
        <Button mode="outline large">Get started</Button>
    </div>
</nav>


<style>
    nav{
        position: fixed;
        z-index: 100;
        width: 100%;
        padding: 40px 32px 0px;
    }
    .nav-wrapper{
        width: 100%;
        height: 48px;
        display: flex;
        justify-content: space-between;
    }
    .image-wrapper{
        width: 194px;
    }
</style>