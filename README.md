# Sassy Website

Create a mockup website as seen in the [reference image folder](./images_reference). 

**Pre start**:

This repository comes with a package.json inculding definitions of dependencies. 
This one uses the sass preprocessor (next to others).

First after cloning, resolve dependencies for the exercise repository:
```bash
npm install
```

From now on you can use the build-scripts, that are defined within the package.json.

To start writing your code use the start script:
```bash
npm run start
```
This will start 'sass' in a watching mode, permanently transpiling from the files inside /scss into /styles.
Also this starts a 'http-server' that delivers the content of the project-directory over http on localhost.

Now, go for it!

**Instructions**: 

* Use sass to create the mockup. 
* Make use of nesting and variables where possible.
* Make sure to design for mobile first! 
* Breakpoints:
    - tablet: ```768px``` 
    - desktop: ```1024px```
* Colors for styling: 
    - Card background color: ```#e0ddb2```
    - Card and aside borders: ```#dad6ab```
    - Color used for nav and footer: ```#016690```
* Use the images in the [images folder](./src/images) for the header and cards.

| mobile | tablet | desktop | 
| --- | --- | --- |
| ![mockup-image-mobile](./images_reference/mobile1.png) ![mockup-image-mobile](./images_reference/mobile2.png) | ![mockup-image-tablet](./images_reference/tablet.png) | ![mockup-image-desktop](./images_reference/desktop.png) |
