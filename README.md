# cFS: Stored Command

[![GitHub release](https://img.shields.io/github/release/lassondesat/cfs-sc.svg)](https://github.com/lassondesat/cfs-sc/releases)

* [Original README](cfs-sc-app-OSS-readme.txt)

## Description

The Stored Command application (SC) is a core Flight System (cFS) application
that is a plug in to the Core Flight Executive (cFE) component of the cFS.

The cFS is a platform and project independent reusable software framework and
set of reusable applications developed by NASA Goddard Space Flight Center. This
framework is used as the basis for the flight software for satellite data
systems and instruments, but can be used on other embedded systems. More
information on the cFS can be found at http://cfs.gsfc.nasa.gov

The SC application allows a system to be autonomously commanded 24 hours a day
using sequences of commands that are loaded to SC. Each command has a time tag
associated with it, permitting the command to be released for distribution at
predetermined times. SC supports both Absolute Time tagged command Sequences
(ATSs) as well as multiple Relative Time tagged command Sequences (RTSs).

## Requirements

* [Operating System Abstraction Layer][osal] 4.1.1 or higher
* [core Flight Executive][cfe] 6.4.1 or higher

## Sources

* https://sourceforge.net/projects/cfs-sc/

[osal]: https://github.com/lassondesat/osal
[cfe]: https://github.com/lassondesat/coreflightexec
