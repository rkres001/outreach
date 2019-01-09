

# Images

## Uploading images

Images referenced in the chalcid website are stored in the `chalcid` project in the Species File Group hosted TaxonWorks.  Contact Nic or Matt if you need access to this project. 

## Adding images to a page

There are several ways to add an image to a page. 

* Preview the size of the image by navigating to that image in TaxonWorks, and clicking on one of the shortend URLs (e.g. that look like this `/s/abc1hi`).
* If that image looks right, copy the URL (right click, copy Image URL in most browsers), the reference it in the page in one of the ways below.

### Referencing an image in a tag
#### When?
Do this when you want to place an image in a pre-defined location, with a pre-defined style.
#### Where?
In the header (top of the page delimited by `---`) of specific templates.  For example the biodiversity template includes these predefined locations:

```
---
card_image: https://your.website.org/s/r81k3u
top_image: https://your.website.org/s/5uftlh
footer_image: https://your.website.org/s/r82j3u
---
```

#### Gotchas!

* _You can not manually alter the size of these images, image sizing is based on the referenced image and the template!_  
* Using a small image may result in it being blown up, making it grainy.

### Using Markdown to reference an image
#### When?
Do this when you have a pre-sized image precisely the same size you want to see in the chalcid website.
#### Where?
Anywhere outside the header tags of the page.

`![Orasema sp.](https://your.website.org/s/jqvje7)`

Note the content in `[]` is the alt text, not the figure heading text.  By default we place a line underneath preceeded with `#####` to include the figure heading:

`![Orasema sp.](https://your.website.org/s/jqvje7)`
`##### This is the figure heading, _with italics`

### Using HTML to reference an image
#### When?
Do this when you have an image that you want to style in a particular manner.  For example the medium size of your image is too small, and you want to use a large image, but large is also too large.
#### Where?
Anywhere outside the header of the page:

`<img src="https://your.website.org/s/0omei0" alt="Pseudochalcura gibbosa: A, ovipositing into Salix; B&C, eggs in Rhododendron bud" width="100%"/>`

There are many different controls (e.g. `width` as above) in an image tag.  A websearch can tell you more.

#### Gotchas!
* HTML image tags DO NOT PREVIEW in a Github issue!
