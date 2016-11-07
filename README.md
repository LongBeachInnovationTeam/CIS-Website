# CIS-Website

Built using [Hugo](https://gohugo.io/) and a modified version of the [Creative](http://themes.gohugo.io/creative/) provided by Hugo.

## Deployment
The static version of the site is compiled into `public/`. Copy everything from `public/` into your deployment target.

## Understanding the directory structure of this Hugo website
CIS-Website - the root of this directory
CIS-Website/data/speakers - stores the yaml files which are used to generate static content for the Awardees section
CIS-Website/config.toml - configuration file that Hugo searches for. The directory structure of a Hugo website (specifically the source files for both content and templates) provides most of the config info Hugo needs, but this config file can explicitly include directions to Hugo regarding how it should render a site, define menus, and set site-wide parameters.