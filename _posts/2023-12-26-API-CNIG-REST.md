---
layout: post
title: API-REST
subtitle: Visor web
cover-img: https://iruelas.files.wordpress.com/2022/05/20220430_2057446536397396045096960.jpg
thumbnail-img: https://www.amcharts.com/wp-content/uploads/2018/09/GeoJSON.png
share-img: /assets/img/path.jpg
tags: [geojson, mappping]
mermaid: true
author: marlucjo
---
   
     
<!-- El visualizador añade los controles scale y backgroundlayers al mapa usando la URL del parámetro src del iframe -->

<style>
. container {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
}

.container iframe {
    position: absolute;
    top:0;
    left: 0;
    width: 100%;
    height: 100%;
</style>

<div class="container">
  <iframe 
  id="CapaRaster" 
  title="CapaRaster" 
  src="https://componentes.cnig.es/api-core/?controls=scale,backgroundlayers"
  allowfullscreen >
</iframe>  

</div>
