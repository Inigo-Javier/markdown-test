# my title
## mi titulo h2
### my title h3
#### my title h4
##### my title h5
###### my title h6

<!-- italic -->
this is an *italic* text~
<!-- strong -->
this is an **strong** text
<!-- strikethrough -->
esto es un ~~texto~~ tachado

<!-- UL -->
* apple
    * apple 2
* orange
* etc

1. apple
    1. apple 2
2. orange
3. etc


[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "Custom title")

> this is a quote

---
___

`console.log('hello world')`

```javascript
import mongoose from "mongoose";
import config from "./config";

(async () => {
  try {
    const db = await mongoose.connect(config.MONGODB_URI, {
      useNewUrlParser: true,
      useUnifiedTopology: true,
      useFindAndModify: false,
      useCreateIndex: true,
    });
    console.log("Mongodb is connected to", db.connection.host);
  } catch (error) {
    console.error(error);
  }
})();
```
```python
print('hello world')
```

```html
<h1>hola mundo</h1>
```
|  Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

![imagen bodega](https://static6.depositphotos.com/1007038/613/i/600/depositphotos_6131906-stock-photo-wine-cellar-in-abbey-of.jpg "foto de bodegas")

![imagen bodega guardada](bodega-porto.webp "foto de bodegas")

<!-- GITHUB MARKDOWN -->
* [x] tarea 1
* [] tarea 2
* [] tarea 3
* [x] tarea 4