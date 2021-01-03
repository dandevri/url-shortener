# url-shortener
> 🔗 Privacy friendly URL shortener using Netlify

Free privacy-friendly URL shortener on custom domain `dndv.nl`. Relies heavily on [Netlify's](https://www.netlify.com)
[`_redirects`](https://www.netlify.com/docs/redirects/). 

The URL's are managed in the `_redirects` file and then Netlify handles all the redirecting.

This domain is deployed on Netlify and then uses _dndv.nl_ as a custom domain.

## Usage

Creates a _random short code_ and adds it to the `_redirects` file.

```
npm run shorten https://example.com 
```

Creates a _short url_ and adds it to the `_redirects` file.

```
npm run shorten https://example.com example
```

## Inspiration

URL shorteners for custom domains  are insanely expensive and trach the sh*t out of their users. I just want a simple way to shorten my url's (e.g. use in video descriptions or slide decks) and don't need any tracking.

Original concept from Kent C. Odds, Carl Rosell & Phil Hawksworth.

## License

[MIT][license] © [Danny de Vries][author]

[author]: https://github.com/dandevri
[license]: license
