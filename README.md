# hugo-quickstart

## Overview

Let's evaluate hugo as a blogging platform vs. Wordpress et al.

I'd like to potentially deploy this in Digital Ocean as an "app" or what not.

Going to follow https://gohugo.io/getting-started/quick-start/


## Setup

```
# force is needed since running this from outside this repo will try to recreate the dir
hugo new site hugo-quickstart --force
cd hugo-quickstart
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke themes/ananke
echo "theme = 'ananke'" >> config.toml
hugo server
```
