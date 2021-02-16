# Mana-Pirma-Majaslapa
<html dir="ltr" lang="en">
  <head>
    <meta charset="utf-8">
    <title>New Tab</title>
    <style>
      body {
        background: #000202;
        margin: 0;
      }

      #oneGoogleBar {
        height: 56px;
      }

      #backgroundImage {
        border: none;
        height: 100%;
        pointer-events: none;
        position: fixed;
        top: 0;
        visibility: hidden;
        width: 100%;
      }

      [show-background-image] #backgroundImage {
        visibility: visible;
      }
    </style>
  </head>
  <body>
    <div id="oneGoogleBar"></div>
    <iframe id="backgroundImage"
        src="chrome-untrusted://new-tab-page/custom_background_image?url=https%3A%2F%2Flh3.googleusercontent.com%2Fproxy%2FnMIspgHzTUU0GzmiadmPphBelzF2xy9-tIiejZg3VvJTITxUb-1vILxf-IsCfyl94VSn6YvHa8_PiIyR9d3rwD8ZhNdQ1C1rnblP6zy3OaI%3Dw3840-h2160-p-k-no-nd-mv">
    </iframe>
    <ntp-app></ntp-app>
    <script type="module" src="new_tab_page.js"></script>
    <link rel="stylesheet" href="chrome://resources/css/text_defaults_md.css">
    <link rel="stylesheet" href="shared_vars.css">
    <div id="oneGoogleBarEndOfBody"></div>
  </body>
</html>