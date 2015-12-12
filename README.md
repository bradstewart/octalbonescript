OctalBoneScript
===============

A more stable, continuously tested and better node.js library for scripting BeagleBone. This is alternative to [bonescript](https://github.com/jadonk/bonescript) library.

__v1.0.0 introduces major BC breaks. Please refer to [releases](https://github.com/theoctal/octalbonescript/releases) to see the changes made in latest version.__

Installation
------------
Recommended method to install OctalBoneScript is to add following line in your project ```package.json``` file.

```json

"octalbonescript" : "1.0.x"

```

After adding this line, you should run ``` npm install ``` command from that project directory to install OBS. Another method is to directly ```cd``` to project directory and run ```npm install octalbonescript``` command.

If you must install OBS globally, you must run following command as root.

```sh

npm install -g --unsafe-perm octalbonescript

```

Please note that OBS does not recommend Linux Angstrom. We strongly recommend that you upgrade your BeagleBone to Debian by following link given below:

[http://beagleboard.org/getting-started#update](http://beagleboard.org/getting-started#update)

Examples
--------
Latest code docs, examples and **migration guide** from original bonescript are available at following link:

[https://github.com/theoctal/octalbonescript/wiki](https://github.com/theoctal/octalbonescript/wiki)

Fork
----
This is a fork of [bonescript](https://github.com/jadonk/bonescript). Some APIs are changed in v1.0.0, and we have changed many things under the hood leading to a much better, more functional and faster version of the original library.

This fork is created to make bonescript more feature rich, faster, fix bugs and make it work in
simulator mode under Mac OSX and Linux.

We encourage you to report issues rightaway if you face any. We will try our best to be of help.
