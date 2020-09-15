<script>
    export let type = "button"
    export let mode = null
    export let color = null
</script>


<button class="{mode} {color}" {type} on:click>
    <slot/>
</button>


<style>
    .outline{
        border: solid 2px var(--white);
        transition: all 0.2s ease;
    }
    .fill{
        border: solid 2px var(--white);
        background-color: var(--white);
        color: var(--black);
        transition: all 0.2s ease;
    }
    .large{
        font-size: 16px;
        padding: 12px 32px;
    }
    .outline:hover{
        background-color: var(--white);
        color: var(--black)
    }
    .fill:hover{
        background-color: rgba(255,255,255,0);
        color: var(--white)
    }
</style>