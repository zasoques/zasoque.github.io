<script>
    import Page from "./Page.svelte";
</script>

<style>
    .container {
        padding: 20px 0;
    }

    .column-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }

    .column {
        flex: 1;
        margin-right: 12px;
    }

    .list-title {
        font-family: var(--condensed), sans-serif;
        font-size: 0.9em;
        margin-bottom: 8px;
    }
</style>

<Page container="inverse-color">
    <div class="container">
        <div class="column-container">
            <div class="column">
                <div class="list-title">Ügranemapotaçamis</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
            </div>
            <div class="column">
                <div class="list-title">Ügranemapotaçamis</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
            </div>
            <div class="column">
                <div class="list-title">Ügranemapotaçamis</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
            </div>
            <div class="column">
                <div class="list-title">Ügranemapotaçamis</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
            </div>
            <div class="column">
                <div class="list-title">Ügranemapotaçamis</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
                <div class="list-item">Sie</div>
            </div>
        </div>
    </div>
</Page>