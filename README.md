## This is a fork from [ars/syntastic-platformio](https://github.com/aars/syntastic-platformio) with minor changes to work with ale instead of syntastic

# ale-platformio.vim

A simple plugin to configure ale c/cpp for platformio projects.

## how does it work?

It looks up the directory tree for `platformio.ini`, 
and tries to parse `.gcc-flags.json` from that directory,
then configures ale accordingly.

## Installation

This plugin is provided as is. It works directly under pathogen. I'm not sure 
about other plugin managers.
