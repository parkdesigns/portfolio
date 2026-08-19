


`magick input.tif +level-colors "blue,white" output.tif`

`exiftool -ImageDescription= unc.seal.highres.tif`

`magick unc.seal.highres.tif -strip unc.seal.highres-raw.tif`

`magick unc.seal.highres-raw.tif +level-colors "blue,white" unc.seal.highres-blue.tif`

magick unc.seal.highres-blue.tif -transparent white unc.seal.highres-blue.tif