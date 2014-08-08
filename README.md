# animate.scss

A powerful, highly customisable SCSS port of Dan Eden's animate.css library.

http://daneden.github.io/animate.css/

Offers feature parity to version 3.2


___TODO:___ _Better documentation. It's coming._


## Installing

```bower install animate-scss```

Once installed, ```@import 'src/_animate'``` from your bower_components folder into your own project (adjusting the path to the import as necessary). Be sure to set any variable overrides beforehand.


## Customisation Options

#### Optional Modules

All of the animations are optional, and easily switched on and off using Sass
variables. This should result in smaller end file sizes, by only enabling the modules
you are using.

You can also override individual module level options and enable every module
with a single variable, which may be useful for development.


#### Vendor Prefixes

Vendor prefixes can be enabled or disabled through a single Sass variable, that
can be set either within the core Animate.scss code, or in any file that includes
the library.

Vendor prefixes are switched off by default, allowing you to use tools such as
Autoprefixer to handle prefixing.

When enabled, all necessary CSS declarations include vendor prefixes for Webkit,
Mozilla, and Opera browsers.


#### Class Naming

All animation class names are defined through a single config file, allowing you
to alter how the output CSS classes are named.

You can also prepend a namespace to all class names, giving you flexibility to use
methods such as BEM, prefixing the animation type with your choice of modifier.
eg. ```(.animation--bounce-in)```


## Contributing

Contributions are greatly appreciated, and Pull Requests are always welcome!

When contributing, please take note of existing coding style, particularly the
use of 4-space soft tabs for indentation, and a trailing linebreak at the end of
files.
