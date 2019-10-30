# VueTsPhaser_Boilerplate

This repository are created just to get to know the combined system of Vue+Ts+Phaser, as such the repository is a boilerplate you can easily set up, run and start develop in. 


# Prerequisite

! NOTE ! This is not a guide on how to install nodjs or npm.

Nodjs sould be installed, which also should contain npm. This was created using node-version: 12.13.0 and npm-version: 6.12.0. If you have an older version, there are no guaranty that this setup will work. 
You can check your node version by runnig the following command in your terminal:

```
node -v
```

similar for npm:

```
npm -v
```


# How to use

Clone the repository, and run the following command inside the root-folder from your terminal:

```
npm install
```

If this fails, you should check your node and npm version-number (See Prerequisite). If this is not the problem, Sivert is a goof, and it is probably his fault.

After installing, everything should be set up to start developing as a normal Vue-project, with the added features of typescript and phaser. 

The boilerplate is set up such that there are one vue-file that handles the app (app.vue), and one that handles all the typescript-files (main.vue). Think of main.vue as a main file, that gains access to typescript files throug the following line

```
import { ClassName } from './ClassNameFile'
```

The ClassName parameter are the class you exported from your ClassNameFile.ts. There shouldn't be any type (.ts) after your filename, only the path and the filename itself.

Primarly will development happen in seperate typescript-files, located in the scr/components dir., using the main.vue as a client. You are free to mess around with App.vue, and everything else, but note that this would be working more with set-up than development. 



# Other

For tutorial and documentation, check out phasers homepage: https://phaser.io/ 











