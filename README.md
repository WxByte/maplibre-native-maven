# MapLibre Native for Android: SatSquatch's build

A Maven repository of [WxByte/maplibre-native](https://github.com/WxByte/maplibre-native), branch
`satsquatch/globe-terrain`: MapLibre Native's globe with 3D terrain, and the additions SatSquatch's custom
layers use (the terrain's heights, draping custom layers onto it). One artifact,
`org.maplibre.gl:android-sdk-opengl` (OpenGL ES; every ABI), at versions `2026.10.19-globe-terrain-ss.N`:

```groovy
repositories {
  maven {
    url 'https://raw.githubusercontent.com/WxByte/maplibre-native-maven/main'
    content { includeModule 'org.maplibre.gl', 'android-sdk-opengl' }
  }
}
```

The iOS Swift package of the same versions is at
[WxByte/maplibre-native-dist](https://github.com/WxByte/maplibre-native-dist).

MapLibre Native is under the BSD 2-Clause License (LICENSE.md).
