Popcorn Interim
===============

A Temporary hosting of templates used for the alpha shown on mozillapopcorn.org:8888

Build Prerequisites
-------------------

* node v0.6 or higher
* npm (comes with node v0.6 installer)

Install/Use Instructions
------------------------

1. Fork this repo locally.
2. `git submodule update --init --recursive` from the root directory
3. `cd butter`
4. `npm install` - Installs all node dependencies
5. `node make` - Builds CSS
6. Switch Back to Root Directory
7. `./build` - Builds everything else
8. Type `localhost:8888` in your browser.
9. Enjoy!
