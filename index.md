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
        
	<h1>AEOn</h1>
        <p>AEOn is a community driven digital currency. Welcome!</p>

        <input type="checkbox" name="accordion" id="official_resources" checked>
        <label for="official_resources"><h2>Official Resources</h2></label>
        <div class="panel">
          {% capture official_resources %}{% include official_resources.md %}{% endcapture %}
          {{ official_resources | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="support" checked>
        <label for="support"><h2>Support</h2></label>
        <div class="panel">
          {% capture support %}{% include support.md %}{% endcapture %}
          {{ support | markdownify }}
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

      </div>
    </div>
  </div>
</main>

<footer>
</footer>

</body>
</html>
