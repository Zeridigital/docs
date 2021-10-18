# Chart types

The following types of charts are available in {{ datalens-full-name }}:

* **Diagrams**:
   - [Line chart](#line-chart)
   - [Area chart](#area-chart)
   - [Normalized area chart](#normalized-area-chart)
   - [Column chart](#bar-chart)
   - [Normalized column chart](#normalized-bar-chart)
   - [Bar chart](#horizontal-bar-chart)
   - [Normalized bar chart](#normalized-horizontal-bar-chart)
   - [Scatter chart](#scatter-chart)
   - [Pie chart](#pie-chart)
   - [Ring chart](#ring-chart)
   - [Tree chart](#tree-chart)
* **Tables**:
   - [Table](#flat-table)
   - [Pivot table](#pivot-table)
* **Geographical map**:
   - [Map](#map-chart)
     - [Point map](#point-map-chart)
     - [Choropleth map](#choropleth-map-chart)
     - [Heat map](#heat-map-chart)
     - [Polyline map](#polyline-map-chart)
* **Other**:
   - [Indicator](#indicator)

## Charts {#charts}

### Line chart {#line-chart}

Displays changes to measures by dimension as a single or multiple horizontal lines.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| X | Dimension. Only one field can be specified |
| Y | Measure.  You can specify multiple measures.<br/>If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names` |
| Y2 | Measure.  Use it to add a second Y-axis to a chart. You can specify multiple measures.<br/>If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names` |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or the `Measure Names` field. Affects the color of lines. `Measure Names` is removed by deleting measures from the Y-axis |
| Sorting | Dimension. Can only use one dimension from the X-axis. Affects the sorting of the X-axis |
| Signatures | Measure. Displays measure values on the chart |

### Area chart {#area-chart}

Displays changes to measures by dimensions as areas, showing the contribution of each line to the total amount.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| X | Dimension. Only one field can be specified |
| Y | Measure. You can specify multiple measures. If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names`. |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or the `Measure Names` field. Affects the color of lines. `Measure Names` is removed by deleting measures from the Y-axis |
| Sorting | Dimension. Can only use one dimension from the X-axis. Affects the sorting of the X-axis |
| Signatures | Measure. Displays measure values on the chart |

### Normalized area chart {#normalized-area-chart}

Normalized area chart that shows the ratio of measures as a percentage.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| X | Dimension. Only one field can be specified |
| Y | Measure. You can specify multiple measures. If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names`. |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or the `Measure Names` field. Affects the color of lines. `Measure Names` is removed by deleting measures from the Y-axis |
| Sorting | Dimension. Can only use one dimension from the X-axis. Affects the sorting of the X-axis |
| Signatures | Measure. Displays measure values on the chart |

### Column chart {#bar-chart}

Displays data as flat vertical bars.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| X | Dimensions. One or two dimensions can be specified |
| Y | Measure. You can specify multiple measures. If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names`. `Measure Names` can be moved to the X-axis |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or the `Measure Names` field. Affects the color of lines. `Measure Names` is removed by deleting measures from the Y-axis |
| Sorting | Dimension or measure. Affects the sorting of columns |
| Signatures | Measure. Displays measure values on the chart |

### Normalized column chart {#normalized-bar-chart}

Normalized column chart that shows the ratio of measures as a percentage.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| X | Dimensions. One or two dimensions can be specified |
| Y | Measure. You can specify multiple measures. If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names`. `Measure Names` can be moved to the X-axis |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or the `Measure Names` field. Affects the color of lines. `Measure Names` is removed by deleting measures from the Y-axis |
| Sorting | Dimension or measure. Affects the sorting of columns |
| Signatures | Measure. Displays measure values on the chart |

### Bar chart {#horizontal-bar-chart}

Displays data as flat horizontal bars.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Y | Dimensions. One or two dimensions can be specified |
| X | Measure. You can specify multiple measures. If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names`. `Measure Names` can be moved to the Y-axis |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or the `Measure Names` field. Affects the color of lines. `Measure Names` is removed by deleting measures from the Y-axis |
| Sorting | Dimension or measure. Affects the sorting of columns |
| Signatures | Measure. Displays measure values on the chart |

### Normalized bar chart {#normalized-horizontal-bar-chart}

Normalized bar chart that shows the ratio of measures.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Y | Dimensions. One or two dimensions can be specified |
| X | Measure. You can specify multiple measures. If you add more than one measure to a section, the **Colors** section contains a dimension named `Measure Names`. `Measure Names` can be moved to the Y-axis |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or the `Measure Names` field. Affects the color of lines. `Measure Names` is removed by deleting measures from the Y-axis |
| Sorting | Dimension or measure. Affects the sorting of columns |
| Signatures | Measure. Displays measure values on the chart |

### Scatter chart {#scatter-chart}

Displays data points for comparing pairs of values. Not supported in [SQL charts](./index.md#sql-charts).

| Section<br/> in the wizard | Description |
| ----- | ---- |
| X | Dimension or measure. Sets the X-axis value |
| Y | Dimension or measure. Sets the Y-axis value |
| Points | Dimension. Specifies the number of points on the chart |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or measure. Affects the color of points |
| Sorting | Measure. Affects the sorting of columns |

### Pie chart {#pie-chart}

Displays the size of elements in a single data series relative to the sum of elements as a circle.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Colors | Dimension. Only one field can be specified |
| Measures | Measure. Only one field can be specified |
| Filters | Dimension or measure. Used as a filter |
| Sorting | Dimension or measure from the **Colors** section. Affects the sorting |
| Signatures | Measure. Displays measure values on the chart |

### Ring chart {#ring-chart}

Displays the size of elements in a single data series relative to the sum of elements as a ring. The number in the center of the ring depends on the type of indicator aggregation. Not supported in [SQL charts](./index.md#sql-charts).

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Colors | Dimension or measure. Only one field can be specified |
| Measures | Measure. Affects the number in the center. Only one field can be specified |
| Filters | Dimension or measure. Used as a filter |
| Sorting | Dimension or measure from the **Colors** section. Affects the sorting |
| Signatures | Measure. Displays measure values on the chart |

### Tree chart {#tree-chart}

Displayed as a set of rectangles. Use this chart to compare proportions in a hierarchy.

Use this chart to compare proportions in a hierarchy.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Dimensions | Dimensions. Determines the hierarchy tree of nested rectangles |
| Size | Measure. One measure that determines the area of a rectangle |
| Filters | Dimension or measure. Used as a filter |
| Colors | Dimension or measure. Affects the shading of rectangles in a chart |

## Tables {#tables}

### Simple table {#flat-table}

Displays data in table format, where the first row defines the names of fields and the remaining rows define their values.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Columns | Dimensions and measures to be used as columns. Field names are used as column headers |
| Filters | Dimension or measure. Used as a filter |
| Colors | Measure. Affects shading of all cells within a row. It may contain only one indicator |
| Sorting | Dimensions and measures specified in the **Columns** section.<br/>You can use multiple dimensions and measures.<br/>The order of fields in a section affects the sorting order of table fields |

### Pivot table {#pivot-table}

Displays data in table format, where rows and columns may contain dimension values and cells at their intersection may contain measures. Not supported in [SQL charts](./index.md#sql-charts).

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Columns | Dimensions |
| Stings | Dimensions |
| Measures | Measures. If you add more than one measure to a section, the **Columns** section contains the `Measure Names` dimension that defines the location of the measure headers. `Measure Names` can be moved to **Rows** |
| Filters | Dimension or measure. Used as a filter |
| Colors | Measure. Affects shading of all cells containing indicators. It may contain only one indicator |
| Sorting | Dimensions and measures specified in the **Columns** and **Rows** sections.<br/>You can use multiple dimensions and measures.<br/>The order of fields in a section affects the sorting order of table fields |

## Map {#map-chart}

Map supports three types of visualization:

* [Point map](#point-map-chart)
* [Choropleth map](#choropleth-map-chart)
* [Heat map](#heat-map-chart)

You can place no more than 5 layers with any visualization type on a map. Layers in the **Map** chart are called geolayers.

_Geolayers_ visualize indicators using points or polygons on the map.

You can do the following operations with geolayers:

* Change name.
* Set transparency level.
* Reorder the layers inside a same visualization type. However, you can't change the order of visualization types (top-to-bottom: point map, chloropleth map, heat map).

You can purchase pre-calculated geolayers from partners in {{ marketplace-name }}.

Not supported in [SQL charts](./index.md#sql-charts).

### Point map {#point-map-chart}

Displays geographical points on the map.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Geopoints | Measure with the `Geopoint` type |
| Size | Measure. Affects the size of the point |
| Layer filters | Dimension or measure. Used as a filter for the current layer |
| General filters | Dimension or measure. Used as a filter for the whole chart |
| Colors | Dimension or measure. Affects the intensity of point fill |
| Tooltips | Dimension or measure. A tooltip that appears when you hover over a point |
| Signatures | Measure. Displayed as text on a point. When used, point size control is blocked |

### Choropleth map {#choropleth-map-chart}

Displays shaded areas on the map.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Geopolygons | Measure with the `Geopolygon` type |
| Layer filters | Dimension or measure. Used as a filter for the current layer |
| General filters | Dimension or measure. Used as a filter for the whole chart |
| Colors | Dimension or measure. Affects the color of points |

### Heat map {#heat-map-chart}

Displays geographical points on the map with different shading intensity.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Geopoints | Measure with the `Geopoint` type |
| Filters | Dimension or measure. Used as a filter for the current layer |
| General filters | Dimension or measure. Used as a filter for the whole chart |
| Colors | Dimension or measure. Affects the intensity of point fill |

### Polyline map {#polyline-map-chart}

Displays lines consisting of sequentially connected points on a map.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Polylines | Measure with the `Geopoint` type |
| Measures | Measure. The value displayed when you hover over a point |
| Grouping | Dimension. Defines a group of points forming a polyline |
| Colors | Dimension or measure. Affects the intensity of line segment fill. A segment is filled in from the first point |
| Order | Dimension. Defines the order for connecting points within a group |
| Layer filters | Dimension or measure. Used as a filter for the current layer |
| General filters | Dimension or measure. Used as a filter for the whole chart |

## Other {#other}

### Indicator {#indicator}

Displays the data as one number.

| Section<br/> in the wizard | Description |
| ----- | ---- |
| Measure | Measure. One measure that determines the indicator value |
| Filters | Dimension or measure. Used as a filter |

#### See also {#see-also}

- [{#T}](../../operations/chart/create-line-chart.md)
- [{#T}](../../operations/chart/create-pivot-table.md)
- [{#T}](../../operations/chart/create-table.md)
- [{#T}](../../operations/chart/create-area-chart.md)
- [{#T}](../../operations/chart/create-column-chart.md)
- [{#T}](../../operations/chart/create-bar-chart.md)
- [{#T}](../../operations/chart/create-pie-chart.md)
- [{#T}](../../operations/chart/create-ring-chart.md)
- [{#T}](../../operations/chart/create-map-chart.md)
- [{#T}](../../operations/chart/publish.md)
