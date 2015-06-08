
Adding your user group to the website
==========

fork this repository
add you group at the end of `src/_data/groups.yml`
submit a pull request it will be merged shortly

Setting up your dev environment
==========

- ruby-2.0.0-p247
- bundler (& run `bundle install`)

Working on scala user groups website
==========
(if using vagrant)
* Ensure your vagrant image is up : `vagrant up`
* Connect to your image : `vagrant ssh`

* Ensure you have the latest js dependencies: `bower install`
* Build the website : `grunt build`
* Start working on the website : `grunt server` (with livereload and fs monitoring)
* Access the watched site from the host : 'http://localhost:4090'
