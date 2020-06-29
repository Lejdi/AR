# AR

Simple AR using GLES30 and [QR scanner](https://github.com/kroegerama/android-kaiteki).  
Application finds QR codes through the camera, and when it finds any, either Utah Teapot (in case QR repreents `"Witaj w Wikipedii!"` string) or Humanoid (in other cases) are rendered on them.  
User can observe the figure from any side. Triangles are recalculated basing on QR geometry and device's sensors.

Minimum sdk version: 23
