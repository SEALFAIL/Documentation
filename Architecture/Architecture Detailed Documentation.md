![SEALFAIL logo](../Graphics/logo-transparent.png) 

# ARCHITECTURE DETAILED DOCUMENTATION

This document details the SEALFAIL architecture and its components to the technical level. It is to be held as the only authority on technical decisions arising from the development process.

## Document information

### Contributors

Sasha Emily Chelsea Murgia <mail@chelsea486mhz.fr>

### Changelog

Wed Jun 15 2022 - Sasha Emily Chelsea Murgia

* Initial document creation

### Contributing

Refer to the SEALFAIL project [documentation repository](https://github.com/SEALFAIL/Documentation) for information regarding contributions.

### Code of conduct (COC)

Contributors are to follow the code of conduct (COC) located at the SEALFAIL project [documentation repository](https://github.com/SEALFAIL/Documentation).

## Part 1 - OpenSCAP

OpenSCAP is to be used during initial installation to harden the system to DISA STIG GUI compliance. This initial hardening is to be performed using the dedicated Anaconda addon, as well as "extra remediation" in the form of post-installation shell scripts in the SEALFAIL kickstarts.

Regular compliance checks are to be performed (interval TBD) by the means of a `systemd` timer, itself calling a `systemd` unit that will execute OpenSCAP.