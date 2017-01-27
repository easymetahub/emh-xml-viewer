[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/easymetahub/emh-xml-viewer)

# \<emh-xml-viewer\>

`emh-xml-viewer` is a div that displays an interactive XML allowing the user to expand and collapse XML data.

This is a polymer wrapper of a javascript based XML Viewer created by Lev Muchnik at (http://www.levmuchnik.net/Content/ProgrammingTips/WEB/XMLDisplay/DisplayXMLFileWithJavascript.html)


## Installation

```
bower install easymetahub/emh-xml-viewer --save
```

## Usage

```
<emh-xml-viewer url="test.xml"></emh-xml-viewer>
<emh-xml-viewer string="<foo><bar/></foo>"></emh-xml-viewer>
```

## Styling

The following custom properties and mixins are also available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--emh-xml-viewer-background-color` | The background color of the viewer. | `lightgrey`
`--emh-xml-viewer-utility-color` | The color of the tag &lt; &gt; | `black`
`--emh-xml-viewer-node-name-color` | The color of the name of the node | `#800080`	
`--emh-xml-viewer-attribute-name-color` | The color of the name of an attribute | `black`
`--emh-xml-viewer-attribute-value-color` | The color of the value of an attribute | `blue`
`--emh-xml-viewer-node-value-color` | The color of the value of the node | `black`
`--emh-xml-viewer-element-border-color` | The color of the vertical lines from a node's start to end  | `#00FF66`
`--emh-xml-viewer-clickable-color` | The color of the '+' and '-' for expanding and collapsing a node | `#800080`


## Credits

Loren Cahlander
Lev Muchnik

## License

MIT License