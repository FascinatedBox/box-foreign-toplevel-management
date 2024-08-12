box-foreign-toplevel-management
===============================

### Overview

This repository contains a Wayland protocol called
box-foreign-toplevel-management (box-tlm for short). Most of the contents of
box-tlm come from the foreign toplevel management protocol in wlroots, called
wl-tlm here.

Documentation for wl-tlm is available [here](https://wayland.app/protocols/wlr-foreign-toplevel-management-unstable-v1)

My additions to wl-tlm are at the bottom of the file for box-tlm.

### Goals

I want to programmatically move and resize windows, as well as add attributes
not available in wl-tlm.
