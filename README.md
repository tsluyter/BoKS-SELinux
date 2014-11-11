BoKS-SELinux-
=============

An SELinux module for FoxT's "BoKS" software

This SELinux module is an experiment, to try and get FoxT Server Control,
aka BoKS, to run properly while under control of SELinux. For more information
on the FoxT Server Control security software, please see http://www.foxt.com

This SELinux module was written by Thomas Sluyter and is made available as-is. 
It is absolutely not production-ready and should not be used to run BoKS systems
in a live environment. While most of BoKS' basic functions have been tested and
verified to work, there are still many features that I cannot test in my current
dev environment. I am only running a vanilla BoKS domain. No LDAP servers, no 
Kerberos, no other fancy features. 
 
Most of the rules in this file were built by using the various SELinux troubleshooting
tools, determining what access needs to be opened up. I've done it all manually, to
ensure that we're not opening up too much. So yeah: trial and error. Lots of it. 

This code is made available under the Creative Commons - Attribution-ShareAlike
license. See http://creativecommons.org/licenses/by-sa/3.0/

You are free:
* to Share & to copy, distribute and transmit the work
* to Remix & to adapt the work
* to make commercial use of the work

Under the following conditions:
Attribution & You must attribute the work in the manner specified by the author or 
licensor (but not in any way that suggests that they endorse you or your use of 
the work.

Share Alike & If you alter, transform, or build upon this work, you may distribute 
the resulting work only under the same or similar license to this one.
