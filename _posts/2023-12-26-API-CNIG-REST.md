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
   src="https://componentes.cnig.es/api-core/?layers=WMS*Minutas_cartogr%C3%A1ficas*https://www.ign.es/wms/minutas-cartograficas*Minutas*true*false**1.3.0*true*true*false,WMTS*https://www.ign.es/wmts/primera-edicion-mtn*catastrones*GoogleMapsCompatible*WMTSMapaRaster*true*image/jpeg*true*true*false,WMS*Montes_de_UP*https://idecyl.jcyl.es/geoserver/ps/wms*znie_cyl_montes_mup*true*false*1.3.0*true*true*true,WMS*V%C3%ADas_pecuarias_CyL_ejes*https://idecyl.jcyl.es/geoserver/am/wms*znie_cyl_vvpp_ejes*true*false*1.3.0*true*true*true,WMS*Cormarcas_forestales*https://idecyl.jcyl.es/geoserver/su/wms*dt_amb_cyl_comarca*true*false*1.3.0*true*true*true&zoom=8&center=-530658,5105352*false&controls=scale,scaleline,panzoom,panzoombar,rotate,backgroundlayers,location&plugins=fulltoc,vectors,ignsearchlocator,information,measurebar,mousesrs,popup,sharemap">
</iframe>
