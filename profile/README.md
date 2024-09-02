# 🌿・NekoNya, the world of nekos

NekoNya is an anime themed website with many things on.

> NekoNya is now back with its new version!

## 📝・To-Do

- [ ] Add more content
- [x] Add more images
- [ ] Create more wrappers for each language
- [x] Create API Docs
- [x] Drink a tea
- [x] Complete rewrite of the structure (the website will become only a frontend site without any apis, and nekonya-storage will become the api)

## ❓・Why us?

- ⚡・Fast
  - The website is made on ExpressJS, and constantly optimized, to bring you the fastest API and deliver you some images fast.
- 📜・Lots of images
  - We try our best at uploading more and more pictures to NekoNya, by downloading randomly from the internet.
- 🖥・API
  - This website also has an API for developers to use, you can use the API to get random images.

## 📚・API

The API is a RESTful API.
```js
const fetch = require('node-fetch');

fetch('https://nekonya.classy.works/api/v1/random/neko')
    .then(res => res.json())
    .then(json => console.log(json));
```
The response will be like this:
```json
{
    "url": "https://cdn.nekonya.classy.works/images/nekos/neko-0001.jpg"
}
```

Please refer to the [official API documentation](https://docs.classydev.fr/nekonya).

## 📜・License

See the license of each project via their LICENSE file.
