Description
===========

Copy of opscode ohai cookbook, for specifically tweaking ipaddresses for vagrant nodes.

See https://github.com/agoddard/street-chef/commit/4c510cb49409b40594a530b16a9af61ca70a49c4

You need specify ohai plugin path in attributes. 
Dafault pth is:
default["vagrant-ohai"]["plugin_path"] = "/etc/chef/vagrant_ohai_plugins"

for me work: 

default['vagrant-ohai']['plugin_path'] = '/opt/chef/embedded/lib/ruby/gems/1.9.1/gems/ohai-6.16.0/lib/ohai/plugins'

