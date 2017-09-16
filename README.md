# Xft
Xft font binding for VisualWorks

## Packages

Load `Xft-All` to load all packages.
Make sure that VW does not load outdated Xft parcels from the `contributed` directory of VW (`Xft-All` tries to avoid loading these versions).

### Xft

A binding for the X FreeType interface library for enumerating and rendering fonts.
Also includes XftFont, a screen font implementation.

### Xft-Integration

Replaces the old XFonts handled by the VM with XftFonts.
Requires a restart once the package is loaded.

### Xft-DesktopIntegration

Gathers font information from the desktop configuration. 
The default text attributes will be resetted according to the default font of the desktop.
Also provides additional settings (Look and Feel > Xft)

### Xft-Performance

Patch: Minimize library/primitive calls when drawing strings with composite fonts