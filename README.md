# Welcome
This project is intended to serve as a lightweight example for creating a [GatsbyJS](https://www.gatsbyjs.org) application that can be deployed to [Zeit Now 2.0](https://zeit.co/now).

You can view a [live demo](https://demo-gatsby-nowv2.now.sh) at [https://demo-gatsby-nowv2.now.sh](https://demo-gatsby-nowv2.now.sh)

This demo has been based off the original tutorial created by Zeit at [https://github.com/zeit/now-examples/tree/master/gatsby](https://github.com/zeit/now-examples/tree/master/gatsby)

## Cheat sheet
```
// Step 1 - Create the default Gatsby app
$ npx gatsby new demo-zeit-now-v2-gatsby
$ cd demo-zeit-now-v2-gatsby/

// Verify your local app is up and running
$ npm start

// Step 2 - Create `now.json` for deployment to Zeit Now v2
//  Note that we have added a "now-build" script to build our app

// Step 3 - Deploy to now
$ npm run deploy

> Deploying ~/repos/demo-zeit-now-v2-gatsby under therobbrennan
> Using project demo-gatsby-nowv2
> Synced 1 file (1.17KB) [981ms]
> https://demo-gatsby-nowv2-abtsbvdcw.now.sh [v2] [in clipboard] [2s]
┌ package.json        Ready               [2m]
├── 0-3a2bd5c9a235c2c48f7f.js (21.56KB)
├── 404.html (9.72KB)
├── 404/index.html (9.7KB)
├── chunk-map.json (554B)
├── component---src-pages-404-js-1af22cf06cd461fb89b9.js (4.55KB)
├── component---src-pages-404-js-1af22cf06cd461fb89b9.js.map (12.29KB)
├── component---src-pages-404-js.a1e3226de724a2570055.css (5.26KB)
├── component---src-pages-index-js-20cc3b8fc80f26983ef6.js (13.54KB)
├── component---src-pages-index-js-20cc3b8fc80f26983ef6.js.map (38.18KB)
├── component---src-pages-index-js.a1e3226de724a2570055.css (5.26KB)
├── component---src-pages-page-2-js-b55efdbe24802f10f9a8.js (4.59KB)
├── component---src-pages-page-2-js-b55efdbe24802f10f9a8.js.map (12.44KB)
├── component---src-pages-page-2-js.a1e3226de724a2570055.css (5.26KB)
├── icons/icon-144x144.png (8.92KB)
├── icons/icon-192x192.png (12.13KB)
├── icons/icon-256x256.png (16.44KB)
├── icons/icon-384x384.png (28.32KB)
├── icons/icon-48x48.png (2.75KB)
├── icons/icon-512x512.png (21.92KB)
├── icons/icon-72x72.png (4.32KB)
├── icons/icon-96x96.png (5.79KB)
├── index.html (11.87KB)
├── manifest.webmanifest (706B)
├── page-2/index.html (9.71KB)
├── pages-manifest-4666a1fb53ffe6f02316.js (901B)
├── pages-manifest-4666a1fb53ffe6f02316.js.map (115B)
├── static/6d91c86c0fde632ba4cd01062fd9ccfa/360b8/gatsby-astronaut.png (1.49KB)
├── 0-3a2bd5c9a235c2c48f7f.js.map (86.7KB)
├── app-b909376d1037b1d46a96.js (181.47KB)
├── static/6d91c86c0fde632ba4cd01062fd9ccfa/5c9de/gatsby-astronaut.png (3.7KB)
├── static/6d91c86c0fde632ba4cd01062fd9ccfa/7e26c/gatsby-astronaut.png (15.56KB)
├── static/6d91c86c0fde632ba4cd01062fd9ccfa/893cf/gatsby-astronaut.png (29.98KB)
├── static/6d91c86c0fde632ba4cd01062fd9ccfa/a2541/gatsby-astronaut.png (9.35KB)
├── static/6d91c86c0fde632ba4cd01062fd9ccfa/fdadc/gatsby-astronaut.png (20.83KB)
├── static/d/1025518380.json (260B)
├── static/d/164/path---404-html-516-62a-NZuapzHg3X9TaN1iIixfv1W23E.json (18B)
├── static/d/173/path---index-6a9-NZuapzHg3X9TaN1iIixfv1W23E.json (18B)
├── static/d/2011440971.json (1.57KB)
├── static/d/44/path---404-22-d-bce-NZuapzHg3X9TaN1iIixfv1W23E.json (18B)
├── static/d/53/path---page-2-fbc-5a8-NZuapzHg3X9TaN1iIixfv1W23E.json (18B)
├── static/d/755544856.json (69B)
├── static/d/920/path---dev-404-page-5-f-9-fab-NZuapzHg3X9TaN1iIixfv1W23E.json (18B)
├── webpack-runtime-586c75e86997621faa61.js (3.46KB)
├── webpack-runtime-586c75e86997621faa61.js.map (15.62KB)
├── webpack.stats.json (2.05KB)
└── app-b909376d1037b1d46a96.js.map (563.29KB)
> Success! Deployment ready [2m]
> Assigning alias demo-gatsby-nowv2.now.sh to deployment demo-gatsby-nowv2-abtsbvdcw.now.sh
> Success! demo-gatsby-nowv2.now.sh now points to demo-gatsby-nowv2-abtsbvdcw.now.sh [2s]

```