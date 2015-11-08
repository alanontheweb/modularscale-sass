# Modular Scale

A modular scale is a list of values that share the same relationship. These values are often used to size type and create a sense of harmony in a design. Proportions within modular scales are all around us from the spacing of the joints on our fingers to branches on trees. These natural proportions have been used since the time of the ancient Greeks in architecture and design and can be a tremendously helpful tool to leverage for web designers.

Ems work especially well with modular scales as their recursive properties mimic modular scales making them more predictable and easier to manage. Pixels and other units work just fine and breakpoints in responsive web design can naturally fall on your scale to create better relevance to your text as all the values in your layout harmonize with each other.

To get started, you need to select a ratio and a base value. The base value is usually your text font size or 1em. Optionally you can add another value to create a double standard modular scale which might be useful to create more options for in-between values. This base size paired with a ratio such as the golden ratio or any musical proportion will create your scale of values which all share this proportion.

## Install

### Compass

* Terminal: `gem install modular-scale`
* Compass config: `require 'modular-scale'`
* SCSS: `@import 'modular-scale';`

### Eyeglass

* Terminal: `npm install modularscale-sass --save-dev`
* SCSS: `@import 'modular-scale'`

### Webpack with sass-loader

* Terminal: `npm install modularscale-sass --save-dev`
* Webpack config: install and use [sass-loader](https://github.com/jtangelder/sass-loader#apply-via-webpack-config)
* SCSS: `@import '~modularscale-sass/stylesheets/modular-scale';`

### Bower

* Terminal: `bower install modular-scale --save-dev`
* SCSS: `@import '../link_to_component_dir/modular-scale';`

### Vanilla Sass

* [Download the latest zip](https://github.com/Team-Sass/modular-scale/releases/latest)
* Extract into your project
* SCSS: `@import 'modular-scale';`

## Using modular scale



## Ratios

Modular scale includes functions for a number of classic design and musical scale ratios. You can add your own ratios as well.

By default ratio is set to `$fifth`.

<table>
  <tr><th>Function         </th><th>Ratio  </th><th>Decimal value</th></tr>
  <tr><td>$phi             </td><td>1:1.618</td><td>1.618        </td></tr>
  <tr><td>$golden          </td><td>1:1.618</td><td>1.618        </td></tr>
  <tr><td>$double-octave   </td><td>1:4    </td><td>4            </td></tr>
  <tr><td>$major-twelfth   </td><td>1:3    </td><td>3            </td></tr>
  <tr><td>$major-eleventh  </td><td>3:8    </td><td>2.667        </td></tr>
  <tr><td>$major-tenth     </td><td>2:5    </td><td>2.5          </td></tr>
  <tr><td>$octave          </td><td>1:2    </td><td>2            </td></tr>
  <tr><td>$major-seventh   </td><td>8:15   </td><td>1.875        </td></tr>
  <tr><td>$minor-seventh   </td><td>9:16   </td><td>1.778        </td></tr>
  <tr><td>$major-sixth     </td><td>3:5    </td><td>1.667        </td></tr>
  <tr><td>$minor-sixth     </td><td>5:8    </td><td>1.6          </td></tr>
  <tr><td>$fifth           </td><td>2:3    </td><td>1.5          </td></tr>
  <tr><td>$augmented-fourth</td><td>1:√2   </td><td>1.414        </td></tr>
  <tr><td>$fourth          </td><td>3:4    </td><td>1.333        </td></tr>
  <tr><td>$major-third     </td><td>4:5    </td><td>1.25         </td></tr>
  <tr><td>$minor-third     </td><td>5:6    </td><td>1.2          </td></tr>
  <tr><td>$major-second    </td><td>8:9    </td><td>1.125        </td></tr>
  <tr><td>$minor-second    </td><td>15:16  </td><td>1.067        </td></tr>
</table>

## [Changelog](https://github.com/Team-Sass/modular-scale/releases)

### License

The MIT License (MIT)

Copyright © 2015 [Scott Kellum](http://www.scottkellum.com/) ([@scottkellum](http://twitter.com/scottkellum)), [Adam Stacoviak](http://adamstacoviak.com/) ([@adamstac](http://twitter.com/adamstac)) and [Mason Wendell](http://thecodingdesigner.com/) ([@codingdesigner](http://twitter.com/codingdesigner))

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

**The software is provided “as is”, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.**
