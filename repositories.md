![SEALFAIL logo](Graphics/logo-transparent.png) 

# GITHUB REPOSITORIES

This document is an extensive list of the SEALFAIL repositories hosted on GitHub, along with a short description of their purpose and content. You should get familiar with them before contributing to the project so as to not duplicate work across different repositories.

## Documentation repositories

**The following repositories do not contain code, only documentation and readable material.**

*	**Path:** `SEALFAIL/Documentation`

	**Description:** The documentation for the SEALFAIL project is stored here.

*	**Path:** `SEALFAIL/postmeritocracy`

	**Description:** Fork of the postmeritocracy manifesto, of which SEALFAIL is a signatory.

## Operating system repositories

**The following repositories are related to the SEALFAIL operating system.**

*	**Path:** `SEALFAIL/iso-builder`

	**Description:** Contains the script used to build the SEALFAIL operating system installation image.

*	**Path:** `SEALFAIL/kernel`

	**Description:** The custom SEALFAIL kernel.

## Vulpes repositories

**The following repositories are related to the Vulpes virtual machine (VM) running withing SEALFAIL.**

Vulpes is the name of the VM used for permanent storage, as well as kernel/memory dumping and system logging.

*	**Path:** `SEALFAIL/vulpes-iso-builder`

	**Description:** Contains the scripts used to build the Vulpes installation image.

## RPM repositories

**The following repositories contain scripts used to build the RPM packages used by SEALFAIL.**

*	**Path:** `SEALFAIL/branding`

	**Description:** Customizes GNOME for SEALFAIL branding.

*	**Path:** `SEALFAIL/rpm-vulpes`

	**Description:** The Vulpes virtual machine running within SEALFAIL.

## LXC RPM repositories

**The following repositories are related to the containerized apps shipped with SEALFAIL.**

Each repository contains a script generating a hardened LXC image of its respective software, then built into an RPM package.

*	**Path:** `SEALFAIL/lxc-gnuradio`

	**Description:** GNU Radio.

*	**Path:** `SEALFAIL/lxc-libreoffice`

	**Description:** LibreOffice suite.

*	**Path:** `SEALFAIL/lxc-thunderbird`

	**Description:** Mozzila Thunderbird mail client.

*	**Path:** `SEALFAIL/lxc-kleopatra`

	**Description:** Kleopatra graphical interface for GPG.

*	**Path:** `SEALFAIL/lxc-torbrowser`

	**Description:** Tor-based navigator forked from Firefox.
