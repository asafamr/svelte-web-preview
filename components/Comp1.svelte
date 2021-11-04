<script context="module">
    export const EXPORTED_STUFF = "LORIS OPOSUM";
</script>

<script lang="ts">
    export let somearg = "strarg";
</script>

{#each [1, 2, 3] as num}
    <div class="someclass">
        {somearg}
        <div>===</div>
    </div>
{/each}

<style>
    .someclass {
        color: red;
    }
    div > div {
        color: sienna;
    }
</style>
