# Vagrant, Ubuntu, nvm

A Vagrantfile that:

* uses the ubuntu/trusty64 box;
* installs nvm;
* installs version of node in .nvmrc file in project root;
* if no .nvmrc file is present installs the latest version of node;
* turns off npm symlinks so it can be used on a Windows host.
