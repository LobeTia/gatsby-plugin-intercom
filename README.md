# gatsby-plugin-intercom

Easily add the [Intercom](https://www.intercom.com/) button to your Gatsby site.

## Install
`npm install --save gatsby-plugin-intercom`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-plugin-intercom`,
    options: {
      appId: 'YOUR_INTERCOM_APP_ID',
      includeInDevelopment: false,
    },
  },
]
```
