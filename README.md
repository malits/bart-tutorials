# bart-tutorials
Suite of tutorials for BART: Berkeley Advanced Reconstruction Toolbox, an open-source library for advanced computational MRI and Image Reconstruction

## Running Locally

1. These notebooks function best with a handful of jupyter notebook extensions. Run `pip install -r requirements.txt` to install them. Run `startup.sh` to configure necessary extensions.

2. Make sure your PATH is configured to find BART. If you get an error when running `bart` from the command line after installing a release from GitHub, run `export PATH=/path/to/bart:$PATH` with your respective path to BART. Additionally, you can run `apt-get install bart` on Ubuntu/Debian or `brew install bart` on OS X. 

## Running from Binder

The following Binder allows you to run BART code directly in your browser! Note that anything involving View - the open-source image viewer for BART - does not currently work in Binder. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/malits/bart-tutorials/master)

