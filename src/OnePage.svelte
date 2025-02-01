<script>
    import Page from "./Page.svelte";
</script>

<style>
    .page {
        height: 100vh;
        display: flex;
    }

    .container {
        margin: auto;
        align-self: center;
        width: 100%;
    }
</style>

<Page>
    <div class="page">
        <div class="container">
            <slot></slot>
        </div>
    </div>
</Page>