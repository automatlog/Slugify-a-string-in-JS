# Slugify-a-string-in-JS
Slugify a string in JavaScript | Node Package Manager| slugify library

Install the slugify library
```bash
npm i slugify
```

Then import it
```js
import slugify from 'slugify'
```

and you can do
```js
const slug = slugify('Testing this')
console.log(slug) //testing-this
```

Note that if the string contains dots or other punctuation, it will not strip that.

To remove that, you can use a regex like this:

```js
slugify('Testing. this!', { remove: /[*+~.,()'"!:@]/g })
```
