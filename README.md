# Custom CSS for PreTeXt books

**Off Label Warning**: This repository contains some hacks that are not officially supported by PreTeXt and could very well break in the future.  Use with caution.

## Instructions

1. Enable a custom css file for the web (and other) targets.  This is done via a string parameter. See the `project.ptx` file for the correct syntax.

2. Put the corresponding `.css` file in the `assets` folder (which you might have to create).

3. Put CSS that overrides the CSS supplied by PreTeXt there.  The inspector tool in a web-browser is useful for seeing what is currently set.  The example file in this repository shows how to override colors.
