# Gallery Table
![Gallery Table Image](/yaml-snippets/gallery-table/assets/gallery-table.png)
## Description
Use a Vertical Gallery styled as a table to display items in rows with :
- Sticky header
- Row selection
- Row action menu
- Easy column management (order, size, visibility)

## Properties
- [x] Using modern controls
- [x] Using preview controls (as of 2024-09-03)

## Usage instructions
All the content inside the table (inside the Gallery) is positionned and visible according to its corresponding header in the "cntTableHeader_T" container.
Values inside the table are 
- Ordered (`X` property)
- Sized (`Width` property)
- Visible (`Visible` property)

according to their header, so we have a true "column" way of desgining the table. 

Simply update the column header label control position (`X` and/or `Width` property) and/or visibility (`Visible` property) to rearrange the Gallery values.

## Author & Contributors
Author : @tchinnin