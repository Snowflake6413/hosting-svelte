<script>
    let provider = 'host.yaoi.tech';
    import Icon from "@iconify/svelte";
    import '@fontsource/inter';
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
        
    <h3><Icon icon="material-symbols:eco" width="24" height="24" />Free</h3>
    <p><Icon icon="tabler:cpu" width="24" height="24" />1 vCPU</p>
    <p><Icon icon="ri:ram-line" width="24" height="24" />2365 MiB of RAM</p>
    <p><Icon icon="mdi:storage" width="24" height="24" />5000 MiB of Storage</p>
    <p>$0/mo</p>
    <button>Get Plan</button>
        </div>

    <div class="plans-card">
    <h3>Standard</h3>
    <p><Icon icon="tabler:cpu" width="24" height="24" />2 vCPU</p>
    <p><Icon icon="ri:ram-line" width="24" height="24" />4 GB of RAM</p>
    <p><Icon icon="mdi:storage" width="24" height="24" />50 GB of Storage</p>
    <p>$5/mo!</p>
    <button>Get Plan</button>
    </div>

    <div class="plans-card">
    <h3>Pro</h3>
    <p><Icon icon="tabler:cpu" width="24" height="24" />4 vCPU</p>
    <p><Icon icon="ri:ram-line" width="24" height="24" />8 GB of RAM</p>
    <p><Icon icon="mdi:storage" width="24" height="24" />250 GB of Storage</p>
    <p>$15/mo</p>
    <button>Get Plan</button>
    </div>

</div>
<div class="about">
    <h1>About host.yaoi.tech</h1>
    <p>Founded in 2026, we provide afforable and reliable hosting services worldwide!</p>
    <p>We use high quality Linux-based servers! For all!</p>
</div>

    <h1>Why choose {provider}?</h1>
<div class="features">
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

    .features {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
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
        text-align: center;
    }

    h1, h2, h3{
        font-weight: 700;
        letter-spacing: -0.5px;
    }

    .plans-card button {
        background: #FE9920;
        color: white;
        border: none;
        padding: 10px 20px;
        border-radius: 12px;
        cursor: pointer;
        margin-top: 15px;
        text-align: center;
    }
</style>