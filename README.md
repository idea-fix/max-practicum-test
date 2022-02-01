# max-practicum-test

Task:

- make package.json file
- init .gitignore
- delivery ready page to GHPages from separate git-branch
- Use Grunt, Gulp or Webpack to build assets (do not touch/edit `./src` and `./index.html`)

The builder must:
- compile JS using babel6 and delivery bundle.js to assets folder,
- CSS should be compiled using Sass (dart-sass, node-sass or sass) with postcss (autoprefixer and cssnano),
- Images: should be copied by task-manager to assets folder
- *(optional) task-manager must optimize images before delivery them to assets folder
- *(optional) task-manager must convert optimized images to `webp` file format

here is modules you probably have to include to project

```json
  "dependencies": {
    "include-media": "~1.4.9",
    "jquery": "~2.2.4",
    "normalize.css": "~5.0.0",
    "jquery-validation": "^1.16.0",
    "slick-carousel": "^1.6.0"
  }
```
