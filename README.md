# Brand images [![Build status](https://img.shields.io/circleci/project/Financial-Times/origami-brand-images.svg)](https://circleci.com/gh/Financial-Times/origami-brand-images) [![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](#licence)

An image set of images of FT editorial brands for use with bylines (eg Brussels blog, Lex)

## Usage

As with all image sets, these are available via the [Image Service](https://www.ft.com/__origami/service/image/v2).

To get a brand image from the Image Service, use the following URL (replace the `product_source` with your product name and `brand_name` with the brand you want)

`https://www.ft.com/__origami/service/image/v2/images/raw/ftbrand-v1:{brand_name}?source={product_source}`

So to get the Brussels Blog:
`https://www.ft.com/__origami/service/image/v2/images/raw/ftbrand-v1:brussels-blog?source=test`

### Getting these brand images in a different colour/format/size

The Image Service will convert these images on the fly if you pass in the right parameters. To find out more about this, please see the [Image Service documentation](https://www.ft.com/__origami/service/image/v2/docs/api)

## Adding or modifying brands

To keep brand images consistent, please follow these guidelines:

- Images should be as high quality as possible (the Image Service will resize them for the appropriate use case)
- Brands must be named as the brand they represent.
- Filenames must be all lower-case hyphenated.
	- **good**: brussels-blog.png, larry-summers-blog.svg
	- **bad**: LunchWithTheFT.png
- Images must be pngs

**Please do not delete brand images without talking to the Origami team who will need to manage the deprecation process**

---
## Questions or comments?

Please [raise an issue](https://github.com/Financial-Times/origami-brand-images/issues), or Internal FT users can contact us via [#origami-support in Slack](https://financialtimes.slack.com/messages/origami-support/).

## Licence

This software is published by the Financial Times under the [MIT licence](http://opensource.org/licenses/MIT).
