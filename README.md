# S1monsAssembly4-VM
In S1monsAssembly4 a heap has been added, to allow dynamic memory allocation.
This heap is managed directly by the virtual machine.

In addition to the heap, a plugin system has been put into place.
This system makes the environment more modular and easy to expand.
A plugin folder can be set with the "--PluginPath" commandline argument.

In v3 of the virtual machine, an interactive mode has been added.
This mode can be invoked with the "-i" commandline argument.
For a list of command do ">>>help".