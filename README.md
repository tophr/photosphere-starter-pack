# photosphere-starter-pack
Templates for getting any image to work as a 360 photosphere or panorama on Facebook

## Introduction
[Facebook now allows still 360 photospheres and panoramas](http://newsroom.fb.com/news/2016/06/introducing-360-photos-on-facebook/) but requires uploaded images to include this meta tag: `<GPano:ProjectionType>equirectangular</GPano:ProjectionType>`

## Usage
The included templates already contain this metadata, or the .xmp file can be used to inject the necessary photosphere metadata in Photoshop. 

### Using a template
The included JPG templates already contain the necessary metadata and can be used as base layers to place your own content on top of. Just make sure to save your file as a .jpg and include the original metadata. Facebook provides its own [additional templates as well](https://www.dropbox.com/sh/70mwlh8k0y4rg0g/AACVNV7hvRZtjEKj4DoJMhCba?dl=0).

### Inject XMP data
1. Open the photo you wish to make into a photosphere in Photoshop. 6000 x 3000 pixel images work best.
2. Go to File > File Info and select the "Raw Data" tab
3. Click “Template” and choose “Import…”
4. Locate `equirectangular-template.xmp` and click “Open.” In the dialog that opens, choose “Keep original metadata, but append matching properties from template”

The new metadata with the equirectangular tag should now be added.

## Further reading
To learn more, visit my blog:
http://tophermcculloch.com/2016/06/make-photo-work-360-photosphere-facebook/

## License
[MIT](https://choosealicense.com/licenses/mit/)
