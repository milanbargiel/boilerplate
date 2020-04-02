# Frontend Boilerplate: 
### Monitor Handlebars-, Sass-, JS-, Image-files for change

**When Nunjucks-File changes:**
- Build html files in dist folder from templates and partials
- Reload Browser

**When Scss file changes:**
- Lint Scss and output errors in console
- Compile Scss to Css and copy to dist folder
- add Vendor prefixes
- Reload Browser

**When JS file changes:**
- Copy to dist folder
- Reload Browser

**When Image file changes:**
- Optimize Image and copy to dist folder
- Reload Browser

### Folder structure after building files
```bash
├── dev
|   ├── images
|   ├── js
|   ├── scss
|   └── templates
├── dist
|   ├── images
|   ├── js
|   ├── index.html
|   └── main.css
└── package.json
```