# -How-to-Scrape-UNSCRAPABLE-data-super-simple-Node.js-API

- https://www.youtube.com/watch?v=YRRW4o-BjEM
- https://raw.githubusercontent.com/RodrigoMvs123/-How-to-Scrape-UNSCRAPABLE-data-super-simple-Node.js-API/main/README.md
- https://github.com/RodrigoMvs123/-How-to-Scrape-UNSCRAPABLE-data-super-simple-Node.js-API/blame/main/README.md
- https://brightdata.com/
- https://nodejs.org/en/

**Terminal**
```bash
npm init
```

- https://nodejs.org/en/download/package-manager/#windows-1
- https://www.smashingmagazine.com/

**Terminal**
```bash
npm i axios cheerio
npm i nodemon
```

## AWS

- https://aws.amazon.com/pt/solutions/case-studies/omeda-studios-case-study/

```
$('div.lb-bold lb-skip-el screen .s result-item.s-asin.sg-col-4-of-16 sg.col.sg-col-4-of-20')
'span.a-size-base-plus.a-color-base.a-text-normal'
```

**Terminal**
```bash
npm run start
```

- https://brightdata.com/

API_TOKEN ( settings / … )

**index.js**
```javascript
const axios = require('axios')
const cheerio = require('cheerio')
const fetchGames async() => {
    try {
        const response = await = axios.get (https://aws.amazon.com/pt/solutions/case-studies/omeda-studios-case-study/)
        const html = response.data 
        const $ = cheerio.load (html)
        const games = []
        $('div.lb-bold lb-skip-el screen .s result-item.s-asin.sg-col-4-of-16 sg.col.sg-col-4-of-20') each((index, el => {}))
        const game = $(el)
        const title = game.find ('span.a-size-base-plus.a-color-base.a-text-normal').text ()
        games.push(title)
        
        })
        return games 
    } catch (err) { 
        console.err (err)
    } 
}
fetchGames().then(games => console.log(games))
```
