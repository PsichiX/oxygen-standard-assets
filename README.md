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

## Included asset modules
- [oxygen-deferred-default-shader-assets](https://www.npmjs.com/package/oxygen-deferred-default-shader-assets)
- [oxygen-deferred-simple-shader-assets](https://www.npmjs.com/package/oxygen-deferred-simple-shader-assets)
- [oxygen-deferred-pbr-shader-assets](https://www.npmjs.com/package/oxygen-deferred-pbr-shader-assets)
