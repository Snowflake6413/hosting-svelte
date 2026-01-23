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
<p>How can we help?</p>

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