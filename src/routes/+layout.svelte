<script>
    import "../app.css";
    import Footer from "../components/Footer.svelte";
    import Header from "../components/Header.svelte";
    import { openModal } from "../store";

    let y;
    $: outerHeight = 0;

    function reroute(href) {
        $openModal = false;
        window.location.href = href;
    }
</script>

<Header></Header>

<slot />

<Footer />

<!-- header
product
conversion
footer -->
