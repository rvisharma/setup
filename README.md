# Webpack Configuration for React

## includes production level configurations.

### scripts

```
start - starts dev server
build - production build
analyze - Bundle Analyzer for Production build
```

- [ ] Docker
- [ ] SSL Setup
- [x] env modes setup
- [x] Babel
  - [ ] babel-polyfill (check if really required?)
  - [x] env preset
  - [x] Babel Dynamic Imports
- [ ] Alias to src
- [ ] Linting and Formatting
  - [x] ESLint
  - [x] Eslint React plugin
  - [ ] Prettier
    - [ ] Hook
    - [ ] config file
- [x] Bundle Analyzer (For Prod Builds)
- [x] Ramda
  - [x] babel ramda plugin
- [ ] Loaders
  - [x] SCSS
  - [x] CSS
  - [x] File Loader (fonts and images)
  - [x] HTMLWebpackPlugin (auto index)
    - [x] html web pack template (better templates)
  - [x] clean web pack plugin (clean dist folder)
  - [ ] https://github.com/tcoopman/image-webpack-loader (image optimisation)
  - [ ] Url loader (base64)
- [x] Caching
- [x] Code Splitting
- [x] Source Maps - eval-source-map (dev) && source-map (production)
- [x] Webpack dev server
- [x] MiniCSSExtract
- [x] Webpack Merge
- [ ] React/Redux/Saga/Router
  - [x] basic React setup
  - [x] Add body with #id to webpack html template
  - [ ] Redux
  - [ ] Redux-saga
  - [ ] React Router
