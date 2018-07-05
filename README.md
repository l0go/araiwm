![araiwm](https://raw.github.com/kaiserschmarrn0/araiwm/master/araiwm.png)

araiwm - arai window manager
----------------------------
manages windows no da

Requirements
------------
XCB header files

Configuration
-------------
araiwm is configured by editing config.h and compiling.

note that config.h contains an option that compiles in support for an external config file. if compiled in, the binary takes the path to this config file as a cli arg. an example config is provided in the repository.

Installation
------------
after completing the configuration steps described above, install using

	make install clean

Launching araiwm
----------------
if config file is enabled, araiwm takes the file's path as it's only arg

Display Managers
----------------
edit the dm/startarai script with programs you want to run along araiwm, like a hotkey manager, for example, then install using
	
	make install_dm clean
