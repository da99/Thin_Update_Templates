Thin\_Upstart\_Templates
========================

Mustache templates you can use to generate 
Upstart conf files from your Thin apps.

Use this with [Thin\_Upstart](https://github.com/da99/Thin_Upstart).

Usage
-----

    cd /my/dir/with/Thin/apps
    gem install Thin_Upstart
    git clone git@github.com:da99/Thin_Upstart_Templates.git templates
    Thin_Upstart --kv " user => deployer "
