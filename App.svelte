<script lang="ts">
    import Comp1, { EXPORTED_STUFF } from "./components/Comp1.svelte";
    async function afunc(inp: string): Promise<number> {
        return 5;
    }
</script>

{EXPORTED_STUFF}
<Comp1 />
{afunc("a")}
<style>
    .unused {
        color: red;

</style>
