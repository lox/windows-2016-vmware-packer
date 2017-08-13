Packer files for Windows 2016 / VMWare Fusion
=============================================

A set of packer files for a minimal Windows 2016 virtual machine. Cobbled together 
from various sources.

Designed in multiple layers, to allow iterating without waiting for hours for the lower
steps to build.

Phase 1
-------

A basic Windows 2016 install with updates applied and chocolatey installed. WinRM is enabled.


References/Sources
------------------

* https://github.com/taliesins/packer-baseboxes/blob/master/hyperv-windows-2016-serverstandard-amd64.json
* https://github.com/StefanScherer/packer-windows
* https://github.com/dylanmei/packer-windows-templates