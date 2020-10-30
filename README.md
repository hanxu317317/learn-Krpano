# learn-Krpano


## Krpano xml 对象描述
```
<krpano>
    <include>
    <preview>
    <image>
      <cube>
      <cubestrip>
      <sphere>
      <cylinder>
      <flat>
      <fisheye>
      <depthmap>
    </image>
    <view>
    <area>
    <display>
    <control>
    <cursors>
    <autorotate>
    <plugin>
    <layer>
      <layer>
      ...
    </layer>
    <hotspot>
    <style>
    <events>
    <action>
    <contextmenu>
    <network>
    <memory>
    <security>
    <textstyle>
    <data>
    <scene>
    <set>
    <debug>
</krpano>
```

### krpano
krpano 是我们每一个xml文档的根. 

```
<krpano version="1.20.8" 
        onstart=""
        basedir="%FIRSTXML%"
        bgcolor=""
        idletime="0.5"
        strict="false"
        showerrors="true"
        logkey="true"
        debugmode="false"
        debugkeys="true"
        debugjsactions="false"
        debugjsplugins="false"
    >
    ...
</krpano>
```

### view
view 可以类比视角相机. 可以控制相机距离圆心的距离, 角度缩放等


|--|--|
|  ----  | ----  |
|hlookat|水平角度, 范围 -180 - 180|
|vlookat|纵向角度, 范围 -180 - 180|

### include
