+++
title = "Conforma Documentation"


# The homepage contents
[extra]
lead = '<b>Conforma</b> is an open source workflow platform designed by <br><a href="https://msupply.foundation/">The mSupply Foundation</a>.'
url = "/docs/about/introduction/"
url_button = "Get started"
repo_version = "GitHub v0.1.0"
repo_license = "Open-source MIT License." 
url = "/docs/introduction/introduction"
repo_url = "https://github.com/openmsupply/application-manager-server"



[[extra.list]]
title = ""
content = '<img src="msupply-foundation-logo square.png" class="light_msupply"><img src="msupply-foundation-logo square-dark.png" class="dark_msupply">'


<li><a href="{{ .Site.BaseURL }}{{ .Site.Params.current_lang }}/">{{ .Site.Params.current_lang | upper }}</a></li>

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="/css/bootstrap.min.css">
  </head>

  <body>
    <!-- Navigation -->
    {% if page.url contains ".es" %}
    <nav class="navbar navbar-expand-md navbar-dark bg-dark mb-4">
      <div class="container-fluid">
        <a class="navbar-brand" href="/">Conforma</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav me-auto mb-2 mb-md-0">
            <li class="nav-item">
              <a class="nav-link" href="/docs/about/introduction.es/">Inicio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/docs/about/introduction/">Inglés</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    {% else %}
    <nav class="navbar navbar-expand-md navbar-dark bg-dark mb-4">
      <div class="container-fluid">
        <a class="navbar-brand" href="/">Conforma</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav me-auto mb-2 mb-md-0">
            <li class="nav-item">
              <a class="nav-link" href="/docs/about/introduction/">Inicio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/docs/about/introduction.es/">Español</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    {% endif %}

    <!-- Page Content -->
    <div class="container">
      {{ content }}
    </div>

    <!-- Bootstrap core JavaScript -->
    <script src="/js/bootstrap.bundle.min.js"></script>
  </body>
</html>


# [[extra.list]]
# title = "Fast by default ⚡️"
# content = 'Get 100 scores on <a href="https://googlechrome.github.io/lighthouse/viewer/?gist=7731347bb8ce999eff7428a8e763b637">Google Lighthouse</a> by default. Doks removes unused css, prefetches links, and lazy loads images.'

# [[extra.list]]
# title = "SEO-ready"
# content = "Use sensible defaults for structured data, open graph, and Twitter cards. Or easily change the SEO settings to your liking."

# [[extra.list]]
# title = "Full text search"
# content = "Search your Doks site with FlexSearch. Easily customize index settings and search options to your liking."

# [[extra.list]]
# title = "Page layouts"
# content = "Build pages with a landing page, blog, or documentation layout. Add custom sections and components to suit your needs."

# [[extra.list]]
# title = "Dark mode"
# content = "Switch to a low-light UI with the click of a button. Change colors with variables to match your branding."

+++
