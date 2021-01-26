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
        <p>Private Digital Cash. Welcome to our home! AEON is an open source project, and therefore it’s life comes from the <b>AEON community</b>; the regular people who decide to follow and help build the project.</p>

        <input type="checkbox" name="accordion" id="resources" checked>
        <label for="resources"><h2><i class="fas fa-book-reader fa-fw" style="color: #1565c0; margin-right:0.5em"></i>Resources</h2></label>
        <div class="panel">
          {% capture resources %}{% include resources.md %}{% endcapture %}
          {{ resources | markdownify }}
        </div>
	
	<input type="checkbox" name="accordion" id="current_releases" checked>
        <label for="current_releases"><h2><i class="fas fa-download fa-fw" style="color: #1565c0; margin-right:0.5em"></i>Current Releases</h2></label>
        <div class="panel">
          {% capture current_releases %}{% include current_releases.md %}{% endcapture %}
          {{ current_releases | markdownify }}
        </div>
	
	<input type="checkbox" name="accordion" id="mining" checked>
        <label for="mining"><h2><i class="fas fa-microchip fa-fw" style="color: #1565c0; margin-right:0.5em"></i>Mining</h2></label>
        <div class="panel">
          {% capture mining %}{% include mining.md %}{% endcapture %}
          {{ mining | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="support" checked>
        <label for="support"><h2><i class="far fa-question-circle fa-fw" style="color: #1565c0; margin-right:0.5em"></i>Support</h2></label>
        <div class="panel">
          {% capture support %}{% include support.md %}{% endcapture %}
          {{ support | markdownify }}
        </div>
	
	<a href="/How-Tos/Contribute/contribute.html" style="text-decoration : none;">
        <label for="contributing"><h2><i class="fas fa-handshake fa-fw" style="color: #1565c0; margin-right:0.5em"></i>Contributing</h2></label>
	</a>

        <input type="checkbox" name="accordion" id="documentation" checked>
        <label for="documentation"><h2><i class="far fa-file fa-fw" style="color: #1565c0; margin-right:0.5em"></i>Documentation</h2></label>
        <div class="panel">
          {% capture documentation %}{% include documentation.md %}{% endcapture %}
          {{ documentation | markdownify }}
        </div>

        <input type="checkbox" name="accordion" id="meeting-logs" checked>
        <label for="meeting-logs"><h2><i class="fas fa-comments fa-fw" style="color: #1565c0; margin-right:0.5em"></i>Community Meeting Logs</h2></label>
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
