<div align="center">

<a href="https://www.jammeryhq.com" title="JammeryHQ" target="_blank">

  <img src="./jammeryhq.png" width="128" />
  
</a>

<p>
Fast-track your JAMstack development & learning
</p>
</div>

<hr />

# About this plugin

Simple plugin for remark to enable the download of remote images.

## Install

```bash
npm install https://github.com/jammeryhq/gridsome-plugin-remark-image-download.git

# or

yarn add https://github.com/jammeryhq/gridsome-plugin-remark-image-download.git
```

## How to use

```js
//gridsome.config.js

module.exports = {
  siteName: 'Gridsome',
  plugins: [
    //...
  ],
  templates: {
    //...
  },
  transformers: {
    //Add markdown support to all file-system sources
    remark: {
      plugins: [
        ['@jammeryhq/gridsome-plugin-remark-image-download', {
          targetPath: './src/assets/contentImages'
        }]
      ]
    }
  }
}
```

## Documentation

You can find the complete documentation here: https://webstone.info/documentation/gridsome-plugin-remark-image-download
