# Compat Report [![coverage](https://img.shields.io/badge/coverage-3%2525-red.svg?style=flat?style=flat-square)](https://github.com/eduardoboucas/compat-report) [![Build Status](https://travis-ci.org/eduardoboucas/compat-report.svg?branch=master)](https://travis-ci.org/eduardoboucas/compat-report)

> A DevTools panel for flagging browser compatibility issues

## Overview

This extension creates a Developer Tools panel that provides a basic overview of potential browser compatibility issues, using data from [MDN](https://github.com/mdn/browser-compat-data). It's still a proof of concept at the moment, so you'll likely find some glitches in the matrix.

## Installation

Compat Report was built using the [WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) standard, so any compatible browser should support it. At this point, it was only tested with **Firefox 57**.

To install it, clone the repository (or [download the ZIP archive](https://github.com/eduardoboucas/compat-report/archive/master.zip)) and follow the instructions on how to [install a temporary add-on](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Temporary_Installation_in_Firefox).

Choose the `dist/` sub-directory as the source for the temporary add-on. After this, you should get a new tab in your Developer Tools panel.

## Usage

To get a compatibility report, navigate to the page you want to inspect and open the **Compatibility** tab.

![Screenshot of compatibility tab](.github/screenshot1.png)
