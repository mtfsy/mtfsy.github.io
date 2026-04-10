+++
title = "Downloading CV..."
+++

<script>
    // Create a temporary link and trigger it
    const link = document.createElement('a');
    link.href = '/static/Musthofa-CV.pdf'; // Path to your actual file
    link.download = 'Musthofa-CV.pdf';
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);

    // Send the user back to the home page after 1 second
    setTimeout(() => { window.location.href = "/"; }, 1000);
</script>

Direct link if download doesn't start: [Download PDF](/static/Musthofa-CV.pdf)