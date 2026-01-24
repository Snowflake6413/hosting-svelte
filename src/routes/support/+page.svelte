<script>
    let provider = 'host.yaoi.tech';
    let email = "hello@host.yaoi.tech";
    let phone = "+1 123-456-7890"
    import Icon from "@iconify/svelte";
    import '@fontsource/inter';
</script>

<footer>
    <div class="content">
        <h3>{provider}</h3>
    </div>
</footer>

<h1>Support</h1>
<p>How can we help you?</p>

<div class="contacts">
    <div class="contact-card">
        <Icon icon="mdi:email-outline" width="24" height="24" />
        <h3>Email</h3>
        <p><a href="mailto:{email}">{email}</a></p>
    </div>
    <div class="contact-card">
        <Icon icon="ic:baseline-phone" width="24" height="24" />
        <h3>Phone</h3>
        <p><a href="tel:{phone}">{phone}</a></p>
    </div>
</div>

<p>We respond to all inquires in less than 24 hours.</p>

<style>

    :global(body) {
        font-family: 'Inter', 'Segoe UI', system-ui, sans-serif;
        font-weight: 500;
        background: linear-gradient(13deg, #FA7921, #FE9920, #ECF8F8);
        color: white;
        min-height: 100vh;
    }

    .contact-card {
        display: flex;
        align-items: center;
        flex-direction: column;
        text-align: center;
        gap: 20px;
        margin: 40px 0;
        border: 2px solid;
        border-radius: 20px;
        padding: 30px;
        width: 200px;
    }

    h1, h3{
        font-weight: 700;
        letter-spacing: -0.5px;
    }
</style>