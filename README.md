# select-all

A Polymer Element that is used to select (or deselect) all items in a list (for example: a list of items from an `<aggregation-display>`).

### Example
```html
    <select-all
      list="[[originalList]]"
      loading="[[loading]]"
      selected="{{selectedList}}">
    </select-all>
```

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
