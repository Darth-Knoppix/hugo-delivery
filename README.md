# Hugo Delivery

**A simple Hugo boilerplate for crafting the perfect site**

This is a boilerplate for using [Hugo](https://gohugo.io/), a static site generator with [Parcel](https://parceljs.org/) for your asset pipeline.

### Quick Overview
Clone this repository and run:

*Yarn*
```bash
cd hugo-delivery
yarn && yarn start // npm install && npm run start
```

*npm*
```bash
cd hugo-delivery
yarn && yarn start // npm install && npm run start
```

Visit http://localhost:1313/ and Hugo should be serving your site.

Make sure to update your *site/config.toml* to ensure everything runs as expected. More on that here - (Configure Hugo)[https://gohugo.io/getting-started/configuration/]

### Development

You need to have Node >= 6 on your local development machine for parcel to do its thing.

#### `yarn start` or `npm run start`
Starts the app in development mode.
Visit http://localhost:1313/ to view it in the browser.

Editing your front-end assets in */src* as well as  */site* will trigger live reload.

### Deployment

#### `yarn build` or `npm run build`
Builds the app in development mode.
Your static site will be built to the */public*, you can then deploy that to almost anywherre you want.

### Tinkering

For more advanced configuration for parcel, take a look at https://parceljs.org/getting_started.html

