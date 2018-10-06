
# Hugo template for Netlify CMS with Netlify Identity

This is a small business template built with [Victor
Hugo](https://github.com/netlify/victor-hugo) and [Netlify
CMS](https://github.com/netlify/netlify-cms), designed and developed
by [Darin Dimitroff](http://www.darindimitroff.com/),
[spacefarm.digital](https://www.spacefarm.digital).

## Getting started

Use our deploy button to get your own copy of the repository.
[![Deploy to Netlify]] 
This will setup everything needed for running the CMS:

* A new repository in your GitHub account with the code
* Full Continuous Deployment to Netlify's global CDN network
* Control users and access with Netlify Identity
* Manage content with Netlify CMS

Once the initial build finishes, you can invite yourself as a user.
Go to the Identity tab in your new site. Click "Invite" and send
yourself an invite. Now you're all set, and you can start editing
content!

## Local Development

Clone this repository, and run `yarn` or `npm install` from the new
folder to install all required dependencies.Then start the
development server with `yarn start` or `npm start`.

## Layouts

The template is based on small, content-agnostic partials that can
be mixed and matched. The pre-built pages showcase just a few of the
possible combinations. Refer to the `site/layouts/partials` folder
for all available partials.

Use Hugo’s `dict` functionality to feed content into partials and
avoid repeating yourself and creating discrepancies.

## CSS

The template uses a custom fork of Tachyons and PostCSS with cssnext
and cssnano.
 To customize the template for your brand, refer to
 `src/css/imports/_variables.css` where most of the important global
 variables like colors and spacing are stored.
