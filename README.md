<!-- 
*** Thanks to Best-README-Template project for providing this template, for more
*** information please refer to following link:
*** https://github.com/othneildrew/Best-README-Template/
 -->


# Preact Progressive Web App Template
Repository created to be a template for Progressive Web Applications built on Preact

## About the project
For the ease of use I have prepared my own template for the future use.

## Getting Started
To clone repo you can use following command:
```sh
git clone https://github.com/yUtopist/preact-progressive-web-app-template.git
```

After cloning the project all you need to do is to install dependencies with:
```sh
npm install
```

And that is it. Vite provides with development server with HTTPS and HTTP. You can
find out specific scripts commands in package.json file.

Preact is used mostly for the "developer expirience" and for lighter build project
compare to React.

## Information
Folder `public/` consists of files that will be included into final build of the 
project, best practice would be to include all media files (jpg/png, svg, mp3) in 
their respective folders inside `public/` folder.

`index.html` file includes meta tag that disables user zooming and scaling of the
application.

`public/.webmanifest` is the reference JSON file for the page to be considered as
Progressive Web App. It contains information for the Application, and needs to be 
updated/changed for each of the projects.

By default shortcuts are excluded, since this template is made for a single page 
application.

Screenshots are not added, since this is an empty template, but by best practices 
it would be a good idea to make them work, the following code would need to be 
included in the `public/.webmanifest` file:
```json
  "screenshots": [
    {
      "src": "/images/screenshot1.png",
      "type": "image/png",
      "sizes": "540x720",
      "form_factor": "narrow"
    },
    {
      "src": "/images/screenshot2.jpg",
      "type": "image/jpg",
      "sizes": "720x540",
      "form_factor": "wide"
    }
  ]
``` 

<!-- ROADMAP -->
## Roadmap

- [ ] Make it work lol

<!-- CONTACT -->
## Contact

Aleksei Stukalov - aleksei@stukalov.dev

Project Link: [https://github.com/yUtopist/preact-progressive-web-app-template](https://github.com/yUtopist/preact-progressive-web-app-template)
