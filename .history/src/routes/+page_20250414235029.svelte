<svelte:head>
    <!-- Meta Information -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Welcome to my personal website!">

    <!-- Custom Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <!-- Rubik -->
    <link href="https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300..900;1,300..900&display=swap" rel="stylesheet">
    <!-- Cantarell -->
    <link href="https://fonts.googleapis.com/css2?family=Cantarell:ital,wght@0,400;0,700;1,400;1,700&family=Rubik:ital,wght@0,300..900;1,300..900&display=swap" rel="stylesheet">

    <!-- Ico Files -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v6.5.2/css/all.css">

    <!-- Tab Title -->
    <title>Home | ktm-p</title>
    <link rel="icon" type="image/x-icon" href="/img/ktmp-logo-white.ico">

    <!-- CSS -->
    <link rel="stylesheet" href="style.css">

    <!-- JS Scripts -->
    <script src="/scripts.js" type="application/javascript" defer></script>
</svelte:head>

<section class="about-me">
    <h1 class="section-head">About Me</h1>
    <div class="about-me-flex">
        <div style="width: 60%; margin-right: 10%">
            <p>I'm Michael, a Junior at UC Berkeley. I am majoring in Pure Mathematics and Computer Science, and minoring in Data Science. I am part of Berkeley's UPE chapter. You can check out my resume <a href="/resume/default/resume.pdf" target="_blank">here</a>

            <br><br>

            My interests revolve mainly around Algorithms, Artificial Intelligence, and Cryptography for Computer Science. In Mathematics, I focus primarily on Algebra and Logic.
            
            <br><br>

            In my free time, I <a href="https://musescore.com/user/32734170" target="_blank">transcribe songs</a> that are stuck in my head. I also have an (unhealthy) obsession with using LaTeX, constantly adding to <a href="https://github.com/ktm-p/LaTeX-Setup" target="_blank">setup.</a></p>
        </div>
        <div>
            <!-- svelte-ignore a11y_img_redundant_alt -->
            <img src="img/dark_raven.png" id="profile-image" alt="Profile Picture">
        </div>
    </div>
</section>

<section class="professional-links">
    <!-- svelte-ignore a11y_consider_explicit_label -->
    <a href="https://github.com/ktm-p" target="_blank">
        <i class="fa fa-brands fa-github" id="github"></i>                
    </a>

    <!-- svelte-ignore a11y_consider_explicit_label -->
    <a href="https://www.linkedin.com/in/michael-pham-a88a17303/" target="_blank">
        <i class="fa-brands fa-linkedin-in" id="linked-in"></i>
    </a>

    <!-- svelte-ignore a11y_consider_explicit_label -->
    <a href="/resume/default/resume.pdf" target="_blank">
        <i class="fa-regular fa-file" id="resume"></i>
    </a>

    <!-- svelte-ignore a11y_consider_explicit_label -->
    <a href="mailto:ktmpham@berkeley.edu" target="_blank">
        <i class="fa-regular fa-envelope" id="email"></i>
    </a>
</section>