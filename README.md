# rovercode Marketing Homepage

This is a static web page used as the rovercode marketing landing page deployed at https://rovercode.com .

It is built using [Hugo](https://gohugo.io/), though at the moment it is just a single index.html.

For responsiveness, menus, and buttons, it uses [Semantic UI](https://semantic-ui.com/).

## Building

1. [Install Hugo](https://gohugo.io/getting-started/installing/).

2. From the directory containing this REAME, run `hugo serve`.

3. In your browser, go to the `http://localhost:XXXX` address that the output of the `hugo serve` command specifies.

## Editing

Currently, all of the html is in layouts/index.html. Images should go in static/assets/images.

You can edit the Semantic UI theme at static/semantic/src/themes/rovercode/site.variables. Page-specific changes can be made in the CSS in index.html.

