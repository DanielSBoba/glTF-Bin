# glTF-Bin

Rhinocerous plugin to export Rhino objects to [glTF Binary](https://www.khronos.org/gltf/) for use on the web/mobile/VR/etc.

Rhino users with questions should go here: https://discourse.mcneel.com/t/gltf-binexport/114378

Bug reports are welcome here.

# For Developers

Everything you need to know about glTF is available on this poster: https://github.com/KhronosGroup/glTF/blob/master/specification/2.0/figures/gltfOverview-2.0.0b.png

Contributions and bug reports are welcome.

## Build Releases and Deploying
This project uses the Rhino7 and above `PackageManger` for managing the user releases.
Building and deploying for both Win and Mac can be done with:
```
$ cd bin/Release/net48
$ /Applications/Rhino\ 7.app/Contents/Resources/bin/yak build
$ /Applications/Rhino\ 7.app/Contents/Resources/bin/yak push gltf-binexporter-XXXXXXX-any.yak
```

# Sponsors
[Stykka ApS](https://stykka.com)
[McNeel](https://rhino3d.com)

# Contributors
[Aske Doerge](https://github.com/Doerge) (original author)

[Joshua Kennedy](https://github.com/jrz371)

[Peter Krattenmacher](https://github.com/pkratten)

[Ali Tehami](https://github.com/alitehami)

# License
MIT but please make PRs if you make improvements.

