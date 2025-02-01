<script>
    import OnePage from "../OnePage.svelte";
    import Page from "../Page.svelte";
    import Footer from "../Footer.svelte";

    import "bootstrap-icons/font/bootstrap-icons.css";
</script>

<style>
    .title {
        font-size: 2em;
        margin-top: 40px;
        font-family: var(--condensed), sans-serif;
    }

    .chevron {
        margin-top: 40px;
        font-size: 1.5em;
        animation: bounce 2s infinite;
    }

    @keyframes bounce {
        0%, 20%, 50%, 80%, 100% {
            transform: translateY(0);
        }
        40% {
            transform: translateY(-10px);
        }
        60% {
            transform: translateY(-5px);
        }
    }
</style>

<OnePage>
    <div class="title">Feloxipùno da Zasoque!</div>
    <div class="content">Aniska, Sat!</div>
    <div class="content chevron" bind:this={ chevron }><i class="bi bi-chevron-down"></i></div>
</OnePage>
<Page>
    <div class="title">Disas ät?</div>
    <div class="content">
        Aniska, disas Ügranemapotaçamisèzasoque. J Scîe d'inosèull'o
        Jélinnamè «<a href="/">zasoque.org</a>», krifè lo dis.
        Diséügranemapotaçamisas Zasoqûm quavùll Taupùmi'm mòdiosàd.
    </div>
</Page>
<Footer />