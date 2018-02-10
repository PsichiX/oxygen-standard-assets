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
