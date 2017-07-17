<div id="preamble" class='body-text'>

The [**FGDC Digital Cartographic Standard for Geologic Map
Symbolization**][fgdc_std], released in 2006, provides guidance and
assets for the preparation of geologic maps. It includes a large array
of reference styles for geologic linework and map symbology.

This repository contains the entire FGDC pattern library extracted to
SVG and PNG, for use on the modern web. In the future, I hope to
incorporate FGDC symbology for linework and geologic symbols.

![A geologic fantasy rendered in Procreate using FGDC pattern brushes](leader.png)

## Motivation

The FGDC reference reference manual is a masterpiece of cartographic design,
and the symbology is unmatched in quality and breadth.
Patterns are [available](https://pubs.usgs.gov/tm/2006/11A02/) as
`.eps` and `.pdf` files, and a subset is packaged as an ESRI ArcGIS `*.style` file.

However, the digital products are difficult to use effectively.
The data formats provided by the USGS are of limited applicability
outside of Adobe Illustrator and the ESRI ecosystem, and are
increasingly dated -- recent
versions of Adobe Illustrator CC have difficulty importing pattern
swatches from the files provided on the FGDC site.

This repackaging of the patterns moves them to modern formats suitable for web-driven maps
and stratigraphic columns. They can also be dependably read by a
wide variety of GIS and graphics software, and flexibly incorporated into derived
packages tailored to specific tasks. Along these lines, this package includes
a catalog of brushes for the iPad drawing app
[*Procreate*](https://procreate.art), which supports the sketching
of geologic maps and stratigraphic columns.

## Prior art and related projects

- The [FGDC standards](https://ngmdb.usgs.gov/fgdc_gds/geolsymstd.php), of course!
- Ryan Clark's [`geocarto`][geocarto], which
  implements a subset of the FGDC standard focused on linework symbols for
  CartoCSS and Mapnik
- *Taconic Musings'* exploration of [geologic mapping in
  QGIS](http://gmcgeology.blogspot.com/2014/05/creating-geologic-maps-in-qgis-strike.html)
- UI icon sets such as [Font Awesome](https://font-awesome.io)

## Usage

The files provided here provide a full representation of the FGDC
pattern symbology, usable within modern web standards.
The SVG files are lossless vectors preserving the full
fidelity of the original patterns, and the PNGs are rasterized versions
that sacrifice some fidelity for flexibility and ease of use. Paletted PNGs, with
lower fidelity and file size, are also provided.

Using SVGs is a *lot more* rendering work for the browser. Thus,
the **png** versions of these symbols are recommended for most
uses. For some uses, it may be desirable to downsample the images
somewhat as well.

Images are addressable with the `id` (shown in bold beneath each symbol
below). For instance, `102-DO.png` or `102-DO.svg` would work.

### Procreate brushes

This product has been processed into a set of brushes for the iPad drawing
program **Procreate**, enabling the drawing of symbology into
stratigraphic columns and maps. These brushes can be individually
imported into Procreate and used from the *Imported Brushes* panel. Some
limitations:

- The pixel dimensions of the pattern stamp can only be changed by
  modifying the brush, using the *Zoom* and *Scale* settings in the
  **Grain** panel of the brush properties window.
- The brushes can only be generated on MacOS, due to the platform-specific
  `plutil` executable.

## Next steps

I would like to use this repository as the centerpiece of an
authoritative collection of resources for geologic symbology. This could
mean several things:

- Add aliases to commonly used lithologic patterns
- Incorporating the linework and point symbology part of the FGDC standards
  (similar to the [`geocarto`][geocarto] implementation)
- Add derived products that can speed adoption of styles on multiple
  platforms
    - QGIS styles
    - CSS stylesheet
    - SVG pattern objects
    - CartoCSS styles

The FGDC standard is comprehensive, but if there is community interest,
we could incorporate other symbology into this set.

[fgdc_std]: https://ngmdb.usgs.gov/fgdc_gds/geolsymstd/download.php
[geocarto]: https://github.com/rclark/geocarto

# Pattern reference

</div>

<div id=patterns></div>