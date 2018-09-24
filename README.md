[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/selvinfehric/paper-countries-dropdown)

# paper-countries-dropdown

This component is based on https://github.com/bluewatertracks/paper-countries. 
Main changes in compare to original component are:
- Search country by country name and/or country dial code
- Preselect country by country code, country name or country dial code
- Improved autoselect
- Design changes according to material design

## Installation

The element can be installed using bower
```
    bower install selvinfehric/paper-countries-dropdown
```
If you want to save it in bower.json file, remember to add flag `--save`
```
    bower install selvinfehric/paper-countries-dropdown --save
```

## Usage

<!--
```
<custom-element-demo>
    <template>
      <script src="../webcomponentsjs/webcomponents-lite.js"></script>
      <link rel="import" href="paper-countries-dropdown.html">
      <style>
        paper-countries-dropdown {
            height: 330px;
	        overflow:hidden;
        }
      </style>
      <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
 -->
 
```html
<paper-countries-dropdown label="Country name" placeholder="Enter country name or dial code"></paper-countries-dropdown>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request 

## Credits

Credits go to https://github.com/bluewatertracks/paper-countries

## License

This project is licensed under the terms of the MIT license.