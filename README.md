# X-Corporation theme for Grav CMS

X-Corporation theme is a port of [X-Corporation](https://uicookies.com/demo/#x_corporation) by [uiCookies](https://uicookies.com/).

Modified and updated by [Aljaxus](https://github.com/aljaxus) for [Webonize](https://webonize.net)

## Features

* Professional user interface
* Responsive and mobile friendly
* Lightweight and fast loading
* Vibrant and clean typography
* Mega, sticky, and offcanvas menu
* Search engine optimized
* Modern browser compatible
* Infinitely and extensively customizable
* Sleek interaction and smooth scrolling

## Installation

### GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install x-corporation

This will install the Gateway theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/x-corporation`.

### Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `x-corporation`.

You should now have all the theme files under

    /your/site/grav/user/themes/x-corporation

### Required Plugins:

* [Error](https://github.com/getgrav/grav-theme-error)
* [Problems](https://github.com/getgrav/grav-plugin-problems)
* [Email](https://github.com/getgrav/grav-plugin-email)
* [Form](https://github.com/getgrav/grav-plugin-form)

## Setup

If you want to set X-Corporation as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: x-corporation`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **x-corporation** folder.

## Configuration with Admin plugin

If you have [Admin plugin](https://github.com/getgrav/grav-plugin-admin) installed, you can fully manage the sub-pages (modular pages) via Admin plugin.

## Updating

Manually updating X-Corporation is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/x-corporation` directory.
* Download the new version of the X-Corporation theme from this repository.
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `x-corporation`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.
