# 🌿・NekoNya

NekoNya is an anime themed website with many things on.

## 📝・To-Do

- [ ] Add more content
- [ ] Add more images
- [ ] Create more wrappers for each language
- [ ] Create API Docs
- [x] Drink a tea

## ❓・Why us?

- ⚡・Fast
- - The website is made on ExpressJS, and constantly optimized, to bring you the fastest API and deliver you some images fast.
- 📜・Free to use, maybe
- - We can't really tell if our images are free to use, we just got 'em downloading from some databases, without filtering. But let's say it is, right?
- 🖥・API
- - This website also has an API for developers to use, you can use the API to get random images.

## 📚・API

The API is pretty simple, you just need to send a request to the API, and it will return you a JSON response.
```js
const fetch = require('node-fetch');

fetch('https://nekonya.js.org/api/v1/random/neko')
    .then(res => res.json())
    .then(json => console.log(json));
```
The response will be like this:
```json
{
    "url": "https://cdn.worldwild.studio/nekos/normal/neko-0001.jpg"
}
```

## 📜・License

All our projects are licensed under the MIT License.