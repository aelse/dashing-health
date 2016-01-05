dashing-health
==============

dashing-health is a widget for Shopify's dashing framework to display system warning and critical counts.

This repo contains the Health widget and a sample dashboard using the widget for multiple environments.

Configuration
=============

Copy the widgets directory to your dashing installation.
You may also copy the sample health dashboard if you wish.

Usage
=====

The widget expects data containing both "criticals" and "warnings". If either is missing it is
treated as an error.

You may send an "error" field, which will result in displaying the given error (not shown
in screenshot).

Screenshot
==========

![image](https://raw.github.com/aelse/dashing-health/master/assets/dashing-health-example.png)
