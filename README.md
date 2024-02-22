# dragncode

#### [Live demo](https://methaqualon.github.io/dragncode/) | [Questions](https://github.com/methaqualon/dragncode/issues)

This is HTML one-filer (like one-liner) for simply create code via moving code blocks for [Puppeteer](https://github.com/puppeteer/puppeteer)

> Puppeteer is a Node.js library which provides a high-level API to control
> Chrome/Chromium over the
> [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/).
> Puppeteer runs in
> [headless](https://developer.chrome.com/articles/new-headless/)
> mode by default, but can be configured to run in full ("headful")
> Chrome/Chromium.


It uses some free and open source libraries, such as [Twitter Bootstrap](https://github.com/twbs/bootstrap), [highlight.js](https://github.com/highlightjs/highlight.js), [JQuery](https://github.com/jquery/jquery), [Sortable](https://github.com/SortableJS/Sortable).
Thanks them for their beautiful products!


The project will develop if there is interest in it from the community, thank you!

### Usage

Just go to the [Live demo](https://methaqualon.github.io/dragncode/) and do what you need.

Move blocks from the left panel to the right, configure them and see result in Javascript code below.

Feel free to download repo and edit any code, open pull requests and create questions/feature requests in the [Issues](https://github.com/methaqualon/dragncode/issues)

> IMPORTANT NOTES
> 
> Tool is not providing puppeteer's initialization code, because for each project it may vary, so you should initialize and stop puppeteer by yourself, and
> place generated by the tool code between this two points.
>
> Don't forget to provide a *page* object to the generated code, and don't forget that generated code must be executed in the async mode (cause of *await* keywords in it).

#### Screenshot
![изображение](https://github.com/methaqualon/dragncode/assets/48207388/7306cc2c-4661-4035-aa75-7b3bdd174505)
