# Archimedes Tux Keyboard

Based off the excellent [Architeuthis dux keyboard](https://github.com/tapioki/cephalopoda/tree/main/Architeuthis%20dux), the goal is to add a third thumb key and see where else this takes me.

Built with [Ergogen](https://github.com/mrzealot/ergogen).

### To Run Locally

**If you do not have Node.js installed** 

Install using [the installer](https://nodejs.org/en/download/) [NVM,](https://github.com/nvm-sh/nvm) or [Chocolatey](https://community.chocolatey.org/packages/nodejs-lts) depending on your platform.  Using the installer usually leads to permission issues with NPM so it's suggested to use either NVM or chocolatey if you don't want to mess with it too much.

Once this is installed run `npm i -g npm` to upgrade NPM to the latest version.

**After Node.js is installed**

Run `npm run patch-footprints` in the base directory.  This is updates one of the footprints to allow for SMD or through-hole only diodes.
