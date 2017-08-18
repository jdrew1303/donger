Donger ヽ༼ຈل͜ຈ༽ﾉ
===============

Generates dongers from [dongerlist.com](http://dongerlist.com).

# Usage

```js
var donger = require('donger');

// 1. Get a random donger
donger() // ヽ༼ •́ ヮ •̀ ༽ᓄ

// 2. Get a random donger by category
donger('dunno') // 乁| ･ 〰 ･ |ㄏ

// 3. Get a specific donger
donger('dunno', 5) // 乁( ⁰͡  Ĺ̯ ⁰͡ ) ㄏ

// 4. Get list of categories
donger.categories // [ 'ameno', 'angry', 'animal', 'brick', 'cool', ...]

// 5. Get everything
donger.dongers // { ameno: [...], angry: [...], animal: [...], ... }
```

**I don't have anything to do with `dongerlist.com`. All the dongers are theirs, not mine.**
