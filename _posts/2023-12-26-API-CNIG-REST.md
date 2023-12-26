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
   
     
<!-- El visualizador crea la capa y realiza el centrado usando la URL del parámetro src del iframe -->
<iframe 
  id="CapaRaster" 
  title="CapaRaster" 
  width="100%" 
  height="500"
  src="https://componentes.cnig.es/api-core/?layers=WMTS*http://www.ign.es/wmts/mapa-raster?*MTN*GoogleMapsCompatible*imagen*true*image/jpeg*true*true*true&center=-1264453.9015709583,4323899.840546544&zoom=5&controls=scale,backgroundlayers">
</iframe>
