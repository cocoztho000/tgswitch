[![Build Status](https://travis-ci.org/warrensbox/terragrunt-switcher.svg?branch=master)](https://travis-ci.org/warrensbox/terragrunt-switcher)
[![Go Report Card](https://goreportcard.com/badge/github.com/warrensbox/terragrunt-switcher)](https://goreportcard.com/report/github.com/warrensbox/terragrunt-switcher)
[![CircleCI](https://circleci.com/gh/warrensbox/terragrunt-switcher/tree/master.svg?style=shield&circle-token=55ddceec95ff67eb38269152282f8a7d761c79a5)](https://circleci.com/gh/warrensbox/terragrunt-switcher)

# Terragrunt Switcher 

<img style="text-allign:center" src="https://s3.us-east-2.amazonaws.com/kepler-images/warrensbox/gshift/smallerlogo.png" alt="drawing" width="120" height="130"/>

<!-- ![gopher](https://s3.us-east-2.amazonaws.com/kepler-images/warrensbox/gshift/logo.png =100x20) -->

The `gshift` command line tool lets you switch between different versions of [terragrunt](https://www.terragrunt.io/). 
If you do not have a particular version of terragrunt installed, `gshift` will download the version you desire.
The installation is minimal and easy. 
Once installed, simply select the version you require from the dropdown and start using terragrunt. 

See installation guide here: [gshift installation](https://warrensbox.github.io/terragrunt-switcher/)

## Installation

`gshift` is available for MacOS and Linux based operating systems.

### Homebrew

Installation for MacOS is the easiest with Homebrew. [If you do not have homebrew installed, click here](https://brew.sh/). 


```ruby
brew install warrensbox/tap/gshift
```

### Linux

Installation for other linux operation systems.

```sh
curl -L https://raw.githubusercontent.com/warrensbox/terragrunt-switcher/release/install.sh | bash
```

### Install from source

Alternatively, you can install the binary from source [here](https://github.com/warrensbox/terragrunt-switcher/releases) 

## How to use:
### Use dropdown menu to select version
<img src="https://s3.us-east-2.amazonaws.com/kepler-images/warrensbox/gshift/gshift.gif" alt="drawing" style="width: 180px;"/>

1.  You can switch between different versions of terragrunt by typing the command `gshift` on your terminal. 
2.  Select the version of terragrunt you require by using the up and down arrow.
3.  Hit **Enter** to select the desired version.

The most recently selected versions are presented at the top of the dropdown.

### Supply version on command line
<img src="https://s3.us-east-2.amazonaws.com/kepler-images/warrensbox/gshift/gshift-v4.gif" alt="drawing" style="width: 170px;"/>

1. You can also supply the desired version as an argument on the command line.
2. For example, `gshift 0.10.5` for version 0.10.5 of terragrunt.
3. Hit **Enter** to switch.

## Additional Info

See how to *upgrade*, *uninstall*, *troubleshoot* here:[More info](https://warrensbox.github.io/terragrunt-switcher/additional)


## Issues

Please open  *issues* here: [New Issue](https://github.com/warrensbox/terragrunt-switcher/issues)






