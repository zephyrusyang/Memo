Base
---

* tags
1. An HTML element usually consists of a start tag and end tag, with the content inserted in between

* Attributes
1. All HTML elements can have attributes
2. Attributes provide additional information about an element
3. Attributes are always specified in the start tag
4. Attributes usually come in name/value pairs like: name="value"



Tags
-----

| name       | attributes                  | memo                                                    |
|------------|-----------------------------|---------------------------------------------------------|
| !doctype   |                             | Docments                                                |
| html       | lang                        |                                                         |
| head       |                             | a container for metadata. Will not be displayed.        |
| style      |                             | element to define internal CSS                          |
| link       | rel/href                    | element to refer to an external CSS file                |
| body       |                             |            |
| br         |                      | Inserts a single line break                             |
| hr         |                      | a thematic break, often displayed as a horizontal rule. |
| pre        |                      | pre-formatted text                                      |
| b          |                      | bold text, without any extra importance.                |
| strong     |                      | strong text, with added semantic "strong" importance.   |
| i          |                      | italic text, without any extra importance.              |
| em         |                      | emphasized text, with added semantic importance.        |
| mark       |                      | Marked or highlighted text                              |
| small      |                      | Smaller text                                            |
| del        |                      | Deleted text (Deleted bar)                              |
| ins        |                      | Inserted text (Underbar)                                |
| sub        |                      | Subscript text                                          |
| sup        |                      | Superscript text                                        |
| q          |                      | a short quotation                                       |
| blockquote |                      | a section that is quoted from another source.           |
| abbr       |                      | an abbreviation or an acronym.                          |
| address    |                      | contact information (author/owner) of document/article. |
| cite       |                      | the title of a work.                                    |
| bdo        | dir                  | Defines the text direction                              |
| iframe     | src/height/width     | An HTML iframe                                          |
| |||


## Block-level Tags
-----

A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

| name       | attributes | memo                                    |
|------------|------------|-----------------------------------------|
| h1,h2..h6  |            | headings                                |
| p          | title      | paragraphs                              |
| div        |            | a section in a document (block-level)   |
| form       |            |                                          |


## Inline Tags
-----

An inline element does not start on a new line and only takes up as much width as necessary.

| name       | attributes                  | memo                                           |
|------------|-----------------------------|------------------------------------------------|
| span       |                             | a section in a document (inline)               |
| a          | href                        | links                                          |
| img        | src/alt/width/height/usemap | images                                         |
| map        | name                        | An image-map is an image with clickable areas. |
| area       | shape/coords/alt/href       | define the clickable areas in the image-map    |


## List Tags
-----

| name       | attributes           | memo                                    |
|------------|----------------------|-----------------------------------------|
| ul         |                      | Unordered HTML List                     |
| ol         |                      | Ordered HTML List                       |
| li         |                      | list item (Ordered/Unordered HTML List) |
| dl         |                      | HTML Description Lists                  |
| dt         |                      | term (name)                             |
| dd         |                      | describes each term                     |


Table Tags
-----

| name       | attributes           | memo                                                                  |
|------------|----------------------|-----------------------------------------------------------------------|
| table      |                      | element to define a table                                             |
| colgroup   |                      | Specifies a group of one or more columns in a table for formatting    |
| col        |                      | Specifies column properties for each column within a colgroup element |
| thead      |                      | Groups the header content in a table |
| tbody      |                      | Groups the body content in a table |
| tfoot      |                      | Groups the footer content in a table |
| caption    |                      | Defines a table caption       |
| tr         |                      | element to define a table row |
| th         | colspan/rowspan      | element to define a table heading |
| td         |                      | element to define a table data |


HTML Comments
-----

Comment tags are used to insert comments in the HTML source code.


Tag Attributes
-----

| name     |                                                    |
|----------|----------------------------------------------------|
| alt      | Specifies an alternative text for an image, when the image cannot be displayed |
| disabled | Specifies that an input element should be disabled                             |
| href     | Specifies the URL (web address) for a link                                     |
| target   | specifies where to open the linked document.                                   |
|          | _blank - Opens in a new window or tab                                          |
|          | _self - Opens in the same window/tab as it was clicked (this is default)       |
|          | _parent - Opens in the parent frame                                            |
|          | _top - Opens in the full body of the window                                    |
|          | framename - Opens in a named frame                                             |
| id       | a unique id for an element                                                     |
| class    | a style for a special type of elements, add a class attribute to the element   |
| src      | Specifies the URL (web address) for an image       |
| style    | Specifies an inline CSS style for an element       |
| title    | Specifies extra information about an element (displayed as a tool tip) |
| colspan  | |
| type     | Ordered HTML List - type of the list item marker |


CSS
-----

| name             | val            |                                   |
|------------------|----------------|-----------------------------------|
| background-color | |background color                                  |
| border           | |a border around an HTML element                   |
| border-collapse  | ||
| border-spacing   | ||
| padding          | |a padding (space) between the text and the border |
| margin           | |a margin (space) outside the border               |
| color            | |text color                                        |
| font-family      | |text fonts                                        |
| font-size        | |text size      |
| text-align       | |text alignment      |
| list-style-type  | disc/circle/square/none |style of the list item marker|
| float            |                         |                             |
