# `@emoji-mart/react`

A React wrapper for [EmojiMart](https://missiveapp.com/open/emoji-mart).

## 🧑‍💻 Usage
```sh
npm install --save @cinefy/emoji-mart @cinefy/emoji-mart-data @cinefy/emoji-mart-react
```

```js
import data from '@cinefy/emoji-mart-data'
import Picker from '@cinefy/emoji-mart-react'

function App() {
  return (
    <Picker data={data} onEmojiSelect={console.log} />
  )
}
```

## 📚 Documentation
See https://github.com/missive/emoji-mart#react
