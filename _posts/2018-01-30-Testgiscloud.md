---
layout: post
title: Test map
---

<iframe src="http://editor.giscloud.com/rest/1/maps/818532/render.iframe?bound=399918.5319880396,6800143.784362406,848451.013965454,7067979.131473662&toolbar=true&popups=true&layerlist=true" width="600" height="400" frameborder="0"></iframe>

<script type='text/javascript' src='http://api.giscloud.com/1/api.js' ></script>
<div id='mapViewer' style='border: 1px solid #C5C5C5; width: 600px; height: 400px'></div>
<script type='text/javascript'>
giscloud.ready(function () {
var mapId = 818532,
    b = new giscloud.Bounds(399918.5319880396, 6800143.784362406, 848451.013965454, 7067979.131473662),
        viewer = new giscloud.Viewer('mapViewer', mapId).bounds(b);
});
</script>
