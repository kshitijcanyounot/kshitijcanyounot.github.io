<!DOCTYPE html>
<html lang="en">

<head>
	<title>3d model</title>
	<meta http-equiv="content-type" content="text/html;charset=utf-8" />
	<meta name="generator" content="Geany 1.37.1" />
	<meta name="viewport" content="width=device-width, initial-scale=1">
	
	
	<link href="style.css" rel="stylesheet">
	<!-- The following libraries and polyfills are recommended to maximize browser support -->
    <!-- NOTE: you must adjust the paths as appropriate for your project -->
    
    <!--  REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
     <script src="https://unpkg.com/@webcomponents/webcomponentsjs@2.1.3/webcomponents-loader.js"></script> 

    <!--  OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
	<!--     <script src="https://unpkg.com/intersection-observer@0.5.1/intersection-observer.js"></script> -->

    <!--  OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
	<!--     <script src="https://unpkg.com/resize-observer-polyfill@1.5.0/dist/ResizeObserver.js"></script> -->
    
    <!--  OPTIONAL: The :focus-visible polyfill removes the focus ring for some input types -->
	<!--
   <script src="https://unpkg.com/focus-visible@5.0.2/dist/focus-visible.js" defer></script>
	-->
</head>

<body>
	<!-- 3D content for your site: -->

    <model-viewer src="segmentation.obj" alt="A 3D intereactive model of a mosquito microCT" shadow-intensity="1" camera-controls auto-rotate ar >
    </model-viewer>


	<!-- 💁 Include both scripts below to support all browsers! -->

	<!-- Loads <model-viewer> for modern browsers: -->
	  <script type="module"
		  src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js">
	  </script>

	<!-- Loads <model-viewer> for old browsers like IE11: -->
	<script nomodule
      src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js">
	</script>
</body>

</html>
