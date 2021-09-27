<p align="right">Language: <a href="https://satakagi.github.io/tribahtinovWebApps/">English</a>, <a href="https://translate.google.co.jp/translate?sl=en&tl=ja&u=https%3A%2F%2Fsatakagi.github.io%2FtribahtinovWebApps%2F">Japanese (Google Translation)</a></p>

# Tri-Bahtinov Mask and original Bahtinov Mask Pattern Generators

## Tri-Bahtinov Mask Pattern Generator WebApps

This is webApps port of [cytan's tri-bahtinov mask generator](https://github.com/cytan299/tribahtinov/).

In addition, a symmetric version with improved sensitivity has been added.

* **[cytan's original tri-bahtinov mask pattern](https://satakagi.github.io/tribahtinovWebApps/Tri-Bahtinov.html)**
* **[Improved sensitivity version](https://satakagi.github.io/tribahtinovWebApps/Tri-Bahtinov_symmetric.html)**
  * **[Tri-Bahtinov_cover for improved sensitivity version](https://satakagi.github.io/tribahtinovWebApps/Tri-Bahtinov_cover.html)** (contributed by jordiblasco [How to use](https://www.cloudynights.com/topic/536410-a-tri-bahtinov-mask-for-sct-collimation-and-focusing/?p=10370496))

## Original Bahtinov Mask Pattern Generator WebApps {#bahtinovwebapps}
Since AstroJargon's site seems to have disappeared, here is a webApps version of the original Bahtinov mask pattern generator for redundancy.

* **[Bahtinov mask generator webApps](https://satakagi.github.io/tribahtinovWebApps/Bahtinov.html)**

## How to make mask {#tomake}
* Laser Cutters
  * In most cases, .svg files can be used as input data for these machines.
* Cutting Plotters
  * Same as above
* 3D Printers
  * The output data is an outline data, so you need to convert it to polygon data using [Inkscape](https://inkscape.org/) etc. [See this video](reports/MakeFilledBahtinovMaskPatternByInkscape.mp4) for the procedure.
  * Next, we need to convert this polygon data (.svg file) into three-dimensional data (.stl file) with thickness. You can use free and easy to use services such as [SVG2STL](http://svg2stl.com/). For other options, you may find [this article](https://all3dp.com/2/svg-to-stl-how-to-convert-svgs-into-3d-printable-stls/) helpful.

## Reports
* [Improve Sensitivity of Tri-Bahtinov Mask](reports/improveSensitivity.html)

## About this site
This site is content that has been moved from https://svg2.mbsrv.net/astro/ to improve accessibility and maintainability by GitHub Pages, maintained by Satoru Takagi.

## License
The original implementation is respected, so it is [GPL3](LICENSE).
