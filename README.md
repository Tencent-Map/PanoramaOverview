##PanoramaOverview 类 {#PanoramaOverview}

###构造函数

<table>
  <tbody>
    <tr>
      <td>构造函数</td>
      <td>说明 </td>
    </tr>
    <tr>
    <td>PanoramaOverview(opts?:<em>[PanoramaOverviewOptions](#PanoramaOverviewOptions)</em></td>
    <td>在给定的地图和街景对象之间建立对应关系</td>
    </tr>
  </tbody>
</table>

###方法

<table>
  <tbody>
    <tr>
      <td>方法</td>
      <td>返回值</td>
      <td>说明</td>
    </tr>
    <tr>
      <td>setMap(map:[Map](http://open.map.qq.com/javascript_v2/doc/map.html#Map))</td>
      <td><code>none</code></td>
      <td>设置街景小地图中的地图对象。</td>
    </tr>
    <tr>
      <td>setPanorama(panorama:[Panorama](http://open.map.qq.com/javascript_v2/doc/panorama.html#Panorama))</td>
      <td><code>none</code></td>
      <td>设置小地图要依赖的街景对象。</td>
    </tr>
  </tbody>
</table>

##PanoramaOverviewOptions 对象规范 {#PanoramaOverviewOptions}

###属性

<table>
  <tbody>
    <tr>
      <td>属性</td>
      <td>类型</td>
      <td>说明</td>
    </tr>
    <tr>
      <td><code>panorama</code></td>
      <td>[Panorama](http://open.map.qq.com/javascript_v2/doc/panorama.html#Panorama)</td>
      <td>场景对象。</td>
    </tr>
    <tr>
      <td><code>map</code></td>
      <td>[Map](http://open.map.qq.com/javascript_v2/doc/map.html#Map)</td>
      <td>地图对象。</td>
    </tr>
  </tbody>
</table>
