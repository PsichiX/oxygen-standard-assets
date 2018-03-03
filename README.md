# Oxygen Game Engine Standard Assets

## Install
```bash
npm install --save oxygen-standard-assets
```

## Usage
**webpack.config.js** - *config.plugins* section:
```javascript
new PackWebpackPlugin([
  { input: [
    'static/assets',
    // include standard assets into generated assets.pack
    '<oxygen-standard-assets>'
  ] }
])
```

## Assets list
- [oxygen-deferred-default-shader-assets](https://www.npmjs.com/package/oxygen-deferred-default-shader-assets)
- [oxygen-deferred-simple-shader-assets](https://www.npmjs.com/package/oxygen-deferred-simple-shader-assets)
