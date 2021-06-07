# Zephyr Developer Summit 2021 Template

This is a non-official template made with [remark](https://github.com/gnab/remark).

It runs in the browser and can be easily deployed with GitHub pages (just enable it in the repo settings). To see the rendered version of this template, go to [martinjaeger.github.io/zds-presentation-template/](https://martinjaeger.github.io/zds-presentation-template/).

## Edit Content

All content is stored in the file `content.md`. Just edit it and you should be able to see the changes immediately.

Official documentation for remark can be found [here](https://github.com/gnab/remark/wiki)

## Local deployment

Install Python and run:

```
python3 -m http.server
```

Afterwards open [http://0.0.0.0:8000](http://0.0.0.0:8000) in your browser.

You can't just open the HTML file in a browser, as it will not be able to load the content.md file.

## PDF generation

```
decktape remark http://0.0.0.0:8000 slieds.pdf --chrome-arg=--disable-web-security --chrome-path /usr/bin/chromium
```

## Contributing

The template is still work in progress. Feel free to submit a PR if you find an issue.
