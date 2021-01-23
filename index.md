<html>
<head>

<link rel="stylesheet" href="https://unpkg.com/flexboxgrid2@7.2.1/flexboxgrid2.css">
  <link href="/libs/fontawesome/css/all.css" rel="stylesheet">

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
        
	<h1>AEON</h1>
        <p>Private Digital Cash. Welcome to our home!</p>

        <input type="checkbox" name="accordion" id="resources" checked>
        <label for="resources"><h2><i class="fas fa-book-reader" style="margin-right:0.5em"></i>Resources</h2></label>
        <div class="panel">
          {% capture resources %}{% include resources.md %}{% endcapture %}
          {{ resources | markdownify }}
        </div>
	
	<input type="checkbox" name="accordion" id="current_releases" checked>
        <label for="current_releases"><h2><i class="fas fa-download" style="margin-right:0.5em"></i>Current Releases</h2></label>
        <div class="panel">
          {% capture current_releases %}{% include current_releases.md %}{% endcapture %}
          {{ current_releases | markdownify }}
        </div>
	
	<input type="checkbox" name="accordion" id="mining" checked>
        <label for="mining"><h2><i class="fas fa-microchip"></i>Mining</h2></label>
        <div class="panel">
          {% capture mining %}{% include mining.md %}{% endcapture %}
          {{ mining | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="support" checked>
        <label for="support"><h2><i class="far fa-question-circle"></i>Support</h2></label>
        <div class="panel">
          {% capture support %}{% include support.md %}{% endcapture %}
          {{ support | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="contributing" checked>
        <label for="contributing"><h2><i class="fas fa-handshake"></i><a href="/How-Tos/Contribute/contribute.html" style="color:black;">Contributing</a></h2></label>

        <input type="checkbox" name="accordion" id="documentation" checked>
        <label for="documentation"><h2><i class="far fa-file" style="margin-right:0.5em"></i>Documentation</h2></label>
        <div class="panel">
          {% capture documentation %}{% include documentation.md %}{% endcapture %}
          {{ documentation | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="meeting-logs" checked>
        <label for="meeting-logs"><h2><i class="fas fa-comments" style="margin-right:0.5em"></i>Community Meeting Logs</h2></label>
        <div class="panel">
          {% capture meeting-logs %}{% include meeting-logs.md %}{% endcapture %}
          {{ meeting-logs | markdownify }}
        </div>

      </div>
    </div>
  </div>
</main>

<footer>
</footer>

</body>
</html>
