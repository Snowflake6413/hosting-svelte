<script>
    let provider = 'host.yaoi.tech';
    import Icon from "@iconify/svelte";
</script>

<footer>
    <div class="content">
        <h3>{provider}</h3>
    </div>
</footer>

<title>{provider}</title>

<div class=wowzers>
    <h2>Hosting for everyone.</h2>
    <p>We are host.yaoi.tech! We provide hosting around the globe!</p>
</div>

<div class="plans">
    <h1>Our plans!</h1>
    <div class="plans-card">
    <h3>Free Server 1</h3>
    <p><Icon icon="tabler:cpu" width="24" height="24" />1 vCPU</p>
    <p><Icon icon="ri:ram-line" width="24" height="24" />1028 MiB of RAM</p>
    <p><Icon icon="mdi:storage" width="24" height="24" />5000 MiB of Storage</p>
    </div>
</div>


<div class="about">
    <h1>About host.yaoi.tech</h1>
    <p>Founded in 2026, we provide afforable and reliable hosting services worldwide!</p>
    <p>We use high quality Linux-based servers! For all!</p>
</div>

<div class="features">
    <h1>Why choose {provider}?</h1>
    <div class="feature-card">
        <Icon icon="mdi:shield-check-outline" width="24" height="24" />
        <h3>99.9% Uptime</h3>
        <p>Reliable infra! This is backed by our SLA guarantees!</p>
    </div>
    <div class="feature-card">
        <Icon icon="carbon:headset" width="32" height="32" />
        <h3>24/7/365 Customer Support</h3>
        <p>Around-the-clock customer support, ready to help on any issues you might have.</p>
    </div>
    <div class="feature-card">
        <Icon icon="ic:baseline-speed" width="24" height="24" />
        <h3>Powerful infra</h3>
        <p>We use state of the art AMD Ryzen processors, high quality SSDs and top-notch memory sticks.</p>
    </div>
</div>

<style>
    footer {
        background: #333;
    }

    .plans-card {
        border: 1px solid #ccc;
        border-radius: 8px;
        padding: 20px;
        margin: 10px 0;
        display: inline-block;
    }

    .feature-card {
        border: 1px solid #ccc;
        border-radius: 8px;
        padding: 20px;
        margin: 10px 0;
        display: inline-block;
        text-align: center;
        width: 200px;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        align-items: center;
        flex-direction: column;
    }

    :global(body) {
        font-family: 'Inter', 'Segoe UI', system-ui, sans-serif;
        font-weight: 500;
        background: linear-gradient(13deg, #FA7921, #FE9920, #ECF8F8);
        color: white;
        min-height: 100vh;
    }

    h1, h2, h3{
        font-weight: 700;
        letter-spacing: -0.5px;
    }
</style>