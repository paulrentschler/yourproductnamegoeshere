Introduction
============
This is a product creation tool for Plone.

Creating new products
=====================

1) Run the shell script to create the new product skeleton

    ./themetransformer.sh myawesometheme "My Awesome Theme"
    ./policytransformer.sh myawesomepolicy "My Awesome Policy"

2) Copy the new product into the src directory of your Zope instance

3) Add the new product name to the [eggs] section of buildout.cfg

4) Add the new product path to develop = section of buildout.cfg

4) Restart Zope

5) Install the new product via Add-ons in your Plone's Site Setup