

## Travis-Build
[![Build Status](https://api.travis-ci.org/agustealo/WordJax.svg?branch=master)](https://travis-ci.org/agustealo/WordJax)

WordJax
===

WordJax is a WordPress starter theme for jumpstarting your next theme development.

Developed by Agustealo Johnson.

Heavily inspired by the awesome WordPress starter theme called `_s`, or `underscores`. A theme meant for hacking so don't use me as a Parent Theme. Instead try turning me into the next, most awesome, WordPress theme out there.

* Just right amount of lean, well-commented, modern, HTML5 templates.
* Helpful 404 template.
* Custom header implementation in `inc/custom-header.php` just add the code snippet found in the comments of `inc/custom-header.php` to your `header.php` template.
* Custom template tags in `inc/template-tags.php` that keep your templates clean and neat and prevent code duplication.
* Some small tweaks in `inc/template-functions.php` that can improve your theming experience.
* A script at `js/navigation.js` that makes your menu a toggled dropdown on small screens (like your phone), ready for CSS artistry. It's enqueued in `functions.php`.
* 2 sample CSS layouts in `layouts/` for a sidebar on either side of your content.
Note: `.no-sidebar` styles are not automatically loaded.
* Smartly organized starter CSS in `style.css` that will help you to quickly get your design off the ground.
* Full support for `WooCommerce plugin` integration with hooks in `inc/woocommerce.php`, styling override woocommerce.css with product gallery features (zoom, swipe, lightbox) enabled.
* Licensed under GPLv2 or later. :) Use it to make something cool.

## Before Installating to your WordPress site

* Download WordJax latest version from the dev branch: [Download Zip](https://github.com/agustealo/WordJax/archive/master.zip).
* unzip WordJax-master.zip.
* Rename WordJax-master floder to WordJax.
* Compress WordJax-master folder
* Install new theme to your WordPress site


Deployment
---------------

1. Download `WordJax` from GitHub. The first thing you want to do is copy the `word_jax` directory and change the name to match your project.
2. Search for `'word_jax'` (inside single quotations) to capture the text domain.
3. Search for `word_jax_` to capture all the function names.
4. Search for `Text Domain: word_jax` in `style.css`.
5. Search for <code>&nbsp;word_jax</code> (with a space before it) to capture DocBlocks.
6. Search for `word_jax-` to capture prefixed handles.

OR

1. Search for: `'word_jax'` and replace with: `'megatherium-is-awesome'`
2. Search for: `word_jax_` and replace with: `megatherium_is_awesome_`
3. Search for: `Text Domain: word_jax` and replace with: `Text Domain: megatherium-is-awesome` in `style.css`.
4. Search for: <code>&nbsp;word_jax</code> and replace with: <code>&nbsp;Megatherium_is_Awesome</code>
5. Search for: `word_jax-` and replace with: `megatherium-is-awesome-`

Then, update the stylesheet header in `style.css`, the links in `footer.php` with your own information and rename `word_jax.pot` from `languages` folder to use the theme's slug. Next, update or delete this readme.

Now you're ready to go! The next step is easy to say, but harder to do: make an awesome WordPress theme. :)

Good luck!