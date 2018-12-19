<html>
<head>

<link rel="stylesheet" href="https://unpkg.com/flexboxgrid2@7.2.1/flexboxgrid2.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">

<!--
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.4/jquery.min.js" type="text/javascript"></script>
-->
</head>
<body>

<header>

</header>

<main>
  <div class="container">
    <div class="row center-xs">
      <div class="col-xs-12 col-lg-10 col-xl-8 text-left">
        <h1>Welcome</h1>
        <p>This site will contain some How-To's and Wherefores of the AEON digital currency.</p>

        <input type="checkbox" name="accordion" id="get-started" checked>
        <label for="get-started"><h2>Get Started</h2></label>
        <div class="panel">
          {% capture get-started %}{% include get-started.md %}{% endcapture %}
          {{ get-started | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="using" checked>
        <label for="using"><h2>Using</h2></label>
        <div class="panel">
          {% capture using %}{% include using.md %}{% endcapture %}
          {{ using | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="recent-news" checked>
        <label for="recent-news"><h2>Recent News</h2></label>
        <div class="panel">
          {% capture recent-news %}{% include recent-news.md %}{% endcapture %}
          {{ recent-news | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="mining" checked>
        <label for="mining"><h2>Mining</h2></label>
        <div class="panel">
          {% capture mining %}{% include mining.md %}{% endcapture %}
          {{ mining | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="contributing" checked>
        <label for="contributing"><h2>Contributing</h2></label>
        <div class="panel">
          {% capture contributing %}{% include contributing.md %}{% endcapture %}
          {{ contributing | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="developer-guides" checked>
        <label for="developer-guides"><h2>Developer Guides</h2></label>
        <div class="panel">
          {% capture developer-guides %}{% include developer-guides.md %}{% endcapture %}
          {{ developer-guides | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="community" checked>
        <label for="community"><h2>Community</h2></label>
        <div class="panel">
          {% capture community %}{% include community.md %}{% endcapture %}
          {{ community | markdownify }}
        </div>
      </div>
    </div>
  </div>
</main>

<footer>
</footer>

</body>
</html>
