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
    '<oxygen-standard-assets>/assets',
    '<oxygen-deferred-default-shader-assets>/assets',
    '<oxygen-deferred-simple-shader-assets>/assets',
    '<oxygen-deferred-pbr-shader-assets>/assets',
    '<oxygen-postprocess-bloom-blur-shader-assets>/assets'
  ] }
])
```

## Included asset modules
- [oxygen-deferred-default-shader-assets](https://www.npmjs.com/package/oxygen-deferred-default-shader-assets)
- [oxygen-deferred-simple-shader-assets](https://www.npmjs.com/package/oxygen-deferred-simple-shader-assets)
- [oxygen-deferred-pbr-shader-assets](https://www.npmjs.com/package/oxygen-deferred-pbr-shader-assets)
- [oxygen-postprocess-bloom-blur-shader-assets](https://www.npmjs.com/package/oxygen-postprocess-bloom-blur-shader-assets)
