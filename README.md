# Chabok web

## Installation
For development and building site you should install [hugo](https://gohugo.io/getting-started/installing/)

## Development
Run `hugo -D serve` to start development server (`-D` is required if you want to build `draft` pages)


## Build
Just run `hugo` and then serve `public` folder

### Use Read more section

```html
{{< extraBox title="TITLE" description="DESCRIPTION" buttonTitle="BUTTON_TITLE" buttonAction="BUTTON_ACTION_URL" image="IMAGE_URL" >}}

```
