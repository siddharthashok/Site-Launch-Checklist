# Site Launch Checklist
A checklist of miscellaneous tasks to do before launching a public website.

## Checklist

### General
- [ ] Strict usage of domain with or without www
- [ ] Correct language set in HTML tag
- [ ] Charset is set
- [ ] HTML is valid
- [ ] 404-page is available

### SEO
* [ ] Pages can be indexed
* [ ] Pages have unique page titles (fewer than 70 characters, includes keywords).
* [ ] Pages have unique meta descriptions (fewer than 156 characters, includes keywords).
* [ ] Pages have keywords (fewer than 10, all words appear in page copy).
* [ ] Images use the alt-attribute
* [ ] Links use a title-attribute
* [ ] A dynamic XML sitemap has been created.
* [ ] The XML sitemap has been submitted to search engines.
* [ ] H1s used for page titles and only one H1 per page
* [ ] HTTPS is used on all pages

### Google Analytics

* [ ] Create [Google Analytics](http://www.google.com/analytics/) account
* [ ] Hook up the GA Tracking Code (typically in our `analytics_lib.js` file)
* [ ] Set up relevant Goals and Funnels
* [ ] Set up [Google Webmaster Tools](https://www.google.com/webmasters/tools/home?hl=en)
* [ ] Verify site in Webmaster Tools with DNS TXT record
* [ ] Link Webmaster Tools to Google Analytics

### Sharing

- [ ] Set up general meta tags
 * `<meta name=“description”>`
 * `<meta name=“author”>`
- [ ] Set up Facebook meta tags & validate [here](https://developers.facebook.com/tools/debug/)
 * `<meta property=“og:site_name”>`
 * `<meta property=“og:title”>`
 * `<meta property=“og:type”>`
 * `<meta property=“og:description”>`
 * `<meta property=“og:url”>`
 * `<meta property=“og:image”>`
- [ ] Set up Twitter meta tags & validate [here](https://cards-dev.twitter.com/validator)
 * `<meta name=“twitter:card”>`
 * `<meta name=“twitter:site”>`
 * `<meta name=“twitter:creator”>`
 * `<meta name=“twitter:description”>` (note that this needs to be under 200 characters)
 * `<meta name=“twitter:title”>`
 * `<meta name=“twitter:url”>`
 * `<meta name=“twitter:image:src”>`
- [ ] Create 2-5 meme images using [Canva](http://canva.com/) or a similar tool

### Mobile

Test on various mobile devices:
- [ ] Scrolling is easy
- [ ] Nav bar works
- [ ] Hoverable things are tappable
- [ ] Charts/maps look ok

### Performance
- [ ] Run the site through https://developers.google.com/speed/pagespeed/insights/
- [ ] Run the site through https://tools.pingdom.com/
- [ ] Leverage browser Caching https://gtmetrix.com/leverage-browser-caching.html
- [ ] Enable gZip compression https://gtmetrix.com/enable-gzip-compression.html
- [ ] Minify CSS & JS
- [ ] CDN is used for static files
- [ ] HTTP/2 is being used
- [ ]
- [ ]

### Rendering
- [ ] Viewport Meta Tag is used correctly
- [ ] Displays & functions correctly in IE10
- [ ] Displays & functions correctly in IE11
- [ ] Displays & functions correctly in Microsoft Edge
- [ ] Displays & functions correctly in Firefox (Windows)
- [ ] Displays & functions correctly in Firefox (Mac)
- [ ] Displays & functions correctly in Chrome (Windows)
- [ ] Displays & functions correctly in Chrome (Mac)
- [ ] Displays & functions correctly in Safari (Mac)
- [ ] Displays & functions correctly in Safari (iOS – Mobile)
- [ ] Displays & functions correctly in Safari (iOS – iPad)
- [ ] Displays & functions correctly in Chrome (iOS – Mobile)
- [ ] Displays & functions correctly in Chrome (iOS – iPad)
- [ ] Displays & functions correctly in Chrome (Android – Mobile)
- [ ] Displays & functions correctly in Chrome (Android – Tablet)
- [ ] Displays & functions correctly on large resolutions

### Accessibility

- [ ] Color Contrast is good (WCAG 2.0)
- [ ] WAI-ARIA roles are used
- [ ] Usage of accessible elements like nav, footer, aside
- [ ] URLs are accessible
- [ ] Keyboard accessibility is available
- [ ] Correct input types are used

### Security

- [ ] HTTPS is used on all pages
- [ ] There is no mixed content on the pages
- [ ] External plugins and trackings get loaded via HTTPS
- [ ] Robots.txt is in use
- [ ] Cross-Site-Scripting is not possible
- [ ] HSTS Header is set
- [ ] Content-Security-Policy is set and only allows specific hosts and no inline scripts


### Useful links
- [ ] https://www.letsvalidate.com

## License

This checklist is licensed under [CC-BY-SA 4.0]()

## Attribution

- https://github.com/datamade/site-launch-checklist (MIT)
- https://github.com/drublic/checklist
- https://humaan.com/checklist/ (CC-BY-SA 4.0)
