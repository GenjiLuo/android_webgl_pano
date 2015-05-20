android_webgl_pano
==================

Make a WebGL explorable panorama from an equirectangular spherical panorama image taken with an Android device.


Notes
-----
- This won't work (in Chrome anyway) with a "file://" URL, but any simple HTTP server should work, i.e. `python -m SimpleHTTPServer` or `ruby -run -e httpd . -p 9090`.
- The file "pano.jpg" should be in the same folder, and X/Y resolution should be powers of 2.
