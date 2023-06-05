# Tucana Linux, A LFS based distro


## Whats different?
This is based on Linux from scratch, yes that linux from scratch.  Although nowadays, Tucana deviates a lot with the addition of lib32 libraries, Vulkan, Wine and other things.  The main selling point is that YOU host the Repos, giving you the ultimate level of control over your PC.  The Repos are also super easy to host and add too (check the wiki), so you can add theming packages, personalized/patched packages or whatever your heart desires, with infinite possibilites no one can yell you what you can or cannot do!

## Install????
Check the wiki on the top bar

# Package Manager
This distro uses the Mercury Package manager it is entirely coded in bash and basically just untars files for simplicity.  Making packages is as easy as DESTDIR installing into a folder and taring it (you can add a depends file).  

Mercury can be used on any system for any project involving packages with depends.  It is a lot easier to make packages and is fast but minimal.  If you just need a package manager for LFS, feel free to use it!
# The Package Mentality
This is a semi-stable partially rolling distro. What I mean by that is there will be a tar released every week to update the stable repo, these tars will contain the newest packages avaliable (Built with Tucana-Build-Scripts) and would essentially make Tucana rolling-release, although these are not guaranteed to function properly.  For those who do not want that, the Stable repo will always be avaliable, and updating from stable-stable and latest-beta-stable is guaranteed to function. For updating, check the issues and the wiki to make sure that there aren't any special commands/scripts that need to be run before the update

# Requesting Packages
File an issue requesting the package, I will get to it as soon as possible, if its a simple package, I will probably have binary avaliable the same day, if its more complex with many depends, it could take a little bit


# Contributing
I am always looking for contibuters, if you want to contribute in any way (graphic design, repo-hosting, building new packages) file an issue or a PR on Tucana-Build-Scripts (https://github.com/xXTeraXx/Tucana-Build-Scripts) 
_________________________________________________________________________________________________________________________________________________________




