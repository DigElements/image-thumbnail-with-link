# image-thumbnail-with-link

A Polymer Element showing an image-thumbnail element and a button-link element.

### Example
```html
<image-thumbnail-with-link
  link="http://link"
  source="http://source"
  style-class="style-class"
  target="_blank"
  text="Click Me"
  click-listener="[[listener]]">
</image-thumbnail-with-link>
```

### Styling

`<image-thumbnail-with-link>` provides the following custom properties and mixins for styling:

Custom property                               | Description                                                    | Default
----------------------------------------------|----------------------------------------------------------------|--------
`--image-thumbnail-with-link-highlight-color` | The background color of the highlighted image.                 | none
`--image-thumbnail-with-link-highlight-style` | The style of the highlighted image.                            | none
`--image-thumbnail-with-link-image-style`     | The style of the element containing the image.                 | none
`--image-thumbnail-with-link-style`           | The style of the element containing the image and button link. | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

