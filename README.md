# openlayersDemo
openlayers地图图层、资源、绘制图层、坐标集群

initMap.html：初始化openlayer地图ol.Map，layer、source、view地图基本配置。

useGdLayer.html：地图图层改变，采用高德图层方法。

mapEventListener.html：地图事件监听、注销。

addPointOrCircle.html：采用ol.Feature添加点和圆，以及设置相关样式。设定中心点ol.geom.Point，设置图形样式ol.style.Style + ol.style.Circle。

addRegularShape.html：采用ol.Feature添加规则多边形（三角形、正方形、五角形…）。设定中心点ol.geom.Point，设置图形样式ol.style.Style + ol.style.RegularShape。

addImgOrSvg.html：采用ol.Feature添加图片、SVG。设定中心点ol.geom.Point，设置图形样式ol.style.Style + ol.style.Icon。

interaction.html：地图交互事件interaction.default、interaction.select，控制地图缩放拖拽滑动等交互事件。

overlay.html：添加地图信息弹窗，ol.Overlay。

drawShape.html：通过ol.interaction.Draw绘制点（Point）、线（LineString）、面（Polygon）

drawRegularShape.html：绘制规则多边形，通过ol.interaction.Draw绘制type:Circle, geometryFunction:ol.interaction.Draw.createRegularPolygon(num)绘制

drawRectangle.html：绘制规则矩形，通过ol.interaction.Draw绘制type:Circle, geometryFunction:ol.interaction.Draw.createBox()绘制

drawShapeUseLine.html：通过type:LineString + maxPoints:2 绘制规则矩形

drawPolygon.html：通过type:Polygon绘制不规则多边形

mapControl.html：地图控件

cluster.html：坐标点集群