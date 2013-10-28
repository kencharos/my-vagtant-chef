create my development environment with vagrant and chef-solo
============================================================

## Usage
1. install vagrant, virtualbox
2. install following vagrant-plugin.  
    ` vagrant plugin install vagrant-omnibus`  
    ` vagrant plugin install vagrant-berkshelf`  
    ` gem i berkshelf`
3. get this project
4. cd this project directory.
5. type ` vagrant up `

## What's install?
+ rbenv
+ ruby (2.0.0-p247)
+ open JDK 7
+ gems (bundle, rails, rspec)
+ mysql(user, password = test)
+ openresty
+ node.js(for rails javascript engen)
+ iptables stop and disables. (because only depeloment use)

## Caution
If  your host OS is winodws, vagrant-ombibus-plugin maybe doesn't work.  
You should comment out ominibus-plugin use in Vagrantfile at such time.

## License
Apache 2.0
