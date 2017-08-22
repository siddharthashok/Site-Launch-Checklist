# Site Launch Checklist
A checklist of miscellaneous tasks to do before launching a public website.

## Checklist

### Web Search Indexing
* [ ] If you have a staging site, tell the search engine robots not to index you with a robots.txt
* [ ] Make sure you allow indexing when you are ready to launch
* [ ] Make sure you handle the www subdomain with DNS redirect

### SEO
* [ ] Pages have unique page titles (fewer than 70 characters, includes keywords).
* [ ] Pages have unique meta descriptions (fewer than 156 characters, includes keywords).
* [ ] Pages have keywords (fewer than 10, all words appear in page copy).
* [ ] Alt tags have been added to every image
* [ ] A dynamic XML sitemap has been created.
* [ ] The XML sitemap has been submitted to search engines.
* [ ] H1s used for page titles and only one H1 per page

### Google Analytics

* [ ] Create [Google Analytics](http://www.google.com/analytics/) account
* [ ] Hook up the GA Tracking Code (typically in our `analytics_lib.js` file)
* [ ] Set up relevant Goals and Funnels
* [ ] Set up [Google Webmaster Tools](https://www.google.com/webmasters/tools/home?hl=en)
* [ ] Verify site in Webmaster Tools with DNS TXT record
* [ ] Link Webmaster Tools to Google Analytics

### Sharing & Rich Snippets

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

### Mobile Friendliness

Test on various mobile devices:
- [ ] Scrolling is easy
- [ ] Nav bar works
- [ ] Hoverable things are tappable
- [ ] Charts/maps look ok

### Printer Friendliness

Dynamic sizing, dark backgrounds, and interactivity don't play well with printers.

Pick one:
- [ ] Make a print stylesheet using a `@media print {}` media query, then add it to your site with `<link rel="stylesheet" type="text/css" href="css/print.css" media="print">`
- or -
- [ ] Use Firefox dev tools to remove offending elements (like sticky footers), alter colors where needed, and screenshot the entire page (here's how: https://stackoverflow.com/a/14830242).
- [ ] Slice the resulting PNG into a multi-page PDF by copy/pasting page-sized chunks into the rich text editor of your choice, i.e. Microsoft Word or Google Docs. Export it to PDF and add it to the directory your images are stored in.
- [ ] Add a link to the printer-friendly version to your website.

### Performance
- [ ] Run the site through https://developers.google.com/speed/pagespeed/insights/
- [ ] Run the site through https://tools.pingdom.com/
- [ ] Leverage browser Caching https://gtmetrix.com/leverage-browser-caching.html
- [ ] Enable gZip compression https://gtmetrix.com/enable-gzip-compression.html
- [ ] Minify CSS & JS

### Miscellaneous Polish
- [ ] add favicons, apple touch icons (http://www.favicomatic.com/)
- [ ] add 404 & 500 error pages

### Accessibility
- [ ] ARIA Landmark Roles specified
- [ ] Semantic headings and structure used
- [ ] Links are clearly recognisable and have :focus state
- [ ] Images use appropriate ALT text
- [ ] Associated label for all form controls
- [ ] Color contrast tested

### Rendering
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

### Useful links
- [ ] https://www.letsvalidate.com

## License

This checklist is licensed under [CC-BY-SA 4.0]()

## Attribution

- https://github.com/datamade/site-launch-checklist (MIT)
- https://humaan.com/checklist/ (CC-BY-SA 4.0)
