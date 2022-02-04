# Frontend Boilerplate:

##### *A simple boilerplate for creating websites with handlebars based templates.*
Inspired by https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/ and https://css-tricks.com/why-npm-scripts/.

### Set up a development server and build files for deployment
- run `yarn install` from your command line to install npm modules
- run `yarn start` to start a local development server that reloads browser on filechange
- when finished developing, copy all files from `out` folder to put on your webserver

### Folder structure
```bash
├── dev
|   ├── assets
|   |   └── images
|   ├── js
|   ├── scss
|   └── templates
├── out
|   ├── assets
|   |   └── images
|   ├── js
|   ├── index.html
|   └── main.css
└── package.json
```

### Npm Scritps based automation
**When Handlebars-File changes:**
- Build html files in `/out` folder from templates and partials
- Reload Browser

**When Scss file changes:**
- Lint Scss and output errors in console
- Compile Scss to Css and copy to out folder
- add Vendor prefixes
- Reload Browser

**When JS file changes:**
- Copy to `/out` folder
- Reload Browser

**When asset file changes:**
- Copy to `/out` folder
- Reload Browser

**When Image file changes:**
- Optimize Image and copy to `/out` folder
- Reload Browser

### Update all node-modules to latest version
- Run `yarn outdated` to see which modules are outdated
- Upgrade all to their latest version with `yarn upgrade --latest`
- Check if everything continues to function as expected