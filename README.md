# Preact Progressive Web App Template
> Repository created to provide a professional template for building Progressive Web Applications with Preact.

## About the Project
This repository serves as a comprehensive template for creating powerful Progressive Web Applications using Preact. Whether you're a seasoned developer or just starting, this template will streamline your development process and enhance your project's performance.

## Getting Started
To clone the repository, execute the following command in your terminal:

```sh
git clone https://github.com/yUtopist/preact-progressive-web-app-template.git
```


Once you have cloned the project, install the dependencies with:

```sh
npm install
```
That's it! Vite provides a development server with both HTTPS and HTTP support. For specific script commands, please refer to the `package.json` file.

Preact has been chosen for its exceptional developer experience and ability to create lighter builds compared to React.

## Folder Structure
The `public/` folder contains files that will be included in the final build of your project. For best practices, consider organizing all media files (jpg/png, svg, mp3) in their respective folders inside `public/`.

### Configuring the Progressive Web App
The `index.html` file includes a meta tag that disables user zooming and scaling of the application, optimizing the experience for mobile users.

In order to define your Progressive Web App, you'll need to update the `public/webmanifest.json` file with the relevant information specific to your project.

Shortcut Exclusion
By default, shortcuts are excluded from this template, as it is primarily designed for single-page applications. However, you may adjust this behavior according to your project requirements.

Adding Screenshots
Although this template is currently empty, you can include screenshots of your application for improved visual representation. To do so, follow these best practices:

Place your screenshots in the `public/images/` folder.
Update the `public/webmanifest.json` file with the relevant screenshot information, as shown in the example below:
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
## Roadmap
[X] Implement core functionality

[  ] Enhance user interface

[  ] Add additional features


## Contact
Feel free to reach out to the project owner if you have any questions or suggestions:

Aleksei Stukalov - aleksei@stukalov.dev

Project Link: [https://github.com/yUtopist/preact-progressive-web-app-template](https://github.com/yUtopist/preact-progressive-web-app-template)

> If you found this template helpful, consider giving it a star on GitHub and sharing it with others! Thank you for using this template, and happy coding!