<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | DogeQuest</title>
    <link rel="shortcut icon" href="TemplateData/favicon.ico">
    <link rel="stylesheet" href="TemplateData/style.css">
    <script src="TemplateData/UnityProgress.js"></script>
    <script src="Build/UnityLoader.js"></script>
    <script>
      var unityInstance = UnityLoader.instantiate("unityContainer", "Build/Muchwowstore.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
  
    <div class="webgl-content">
    <div>A preview, while the game is still in progress.	Consider Donating to : DFMhTR3taFWAdUY8kL3T1nqpwxS6xgmUhS  </div>
      <div id="unityContainer" style="width: 1920px; height: 1080px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="unityInstance.SetFullscreen(1)"></div>
        <div class="title">DogeQuest</div>
      </div>
    </div>
  </body>
</html>
